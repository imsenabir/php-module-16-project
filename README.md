# Module 16 Assignment – Personal Portfolio

Submission for **Module 16 Assignment** in the Laravel course. This project covers:

- Conversion of the [Personal Bootstrap Template](https://startbootstrap.com/theme/personal) to Laravel Blade
- Database schema design via Laravel migrations
- Functional contact form with validation, session-based feedback, logging, and redirection
- Clean, organized codebase with unnecessary files removed

## 🔧 Features

### 1. 🧩 Blade Template Integration
- HTML template refactored into Blade components
- Layout file with `@yield` sections
- Header, footer, and reusable elements as partials

### 2. 🗃️ Database Migrations
- Schema based on provided diagram: [Database Diagram Link](https://drive.google.com/)
- Models and relationships implemented using migrations

### 3. ✉️ Contact Form
- Contact form submits via `POST`, validates input, and stores data
- Success message shown using session
- Submission logged with Laravel logging
- Redirects to confirmation page with submitted info

---

## 📁 Project Structure

- `resources/views/layouts`: Blade layout
- `resources/views/components`: Header/footer partials
- `routes/web.php`: Route definitions
- `app/Http/Controllers/ContactController.php`: Handles form logic
- `database/migrations`: Migration files
- `public/`: Template assets
- `project.sql`: Database dump

---

## 🎥 Presentation Video

Watch the project walkthrough:  
🔗 [Google Drive Video Link](https://drive.google.com/)

Database Diagram:  
<img width="1851" height="831" alt="image" src="https://github.com/user-attachments/assets/" />

---

## 🧠 Getting Started

1. Clone the repo
2. Run `composer install`
3. Set up `.env` and run `php artisan migrate`
4. Import `project.sql` if needed
5. Start server: `php artisan serve`
6. Open in browser

---

## 📌 Notes

- Excludes files like `node_modules`, `vendor`, `.vscode`, etc.
- All features tested and verified
- Codebase cleaned of unused/commented code

---

## 📝 License

Open-source project for educational use in Laravel learning.
