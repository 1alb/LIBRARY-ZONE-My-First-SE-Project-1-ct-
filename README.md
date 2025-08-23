📚 Library Zone

Library Zone is a simple web-based application to digitally manage books and library services. It provides a clean navigation menu with sections for Home, Books (Fiction, Non-Fiction, E-Books), Duration, Payment, Contact, Login, Admin, Register, and Feedback. Users can browse different book categories, check reading duration, and access payment details through iframes for smooth navigation. The project also includes a feedback form, user registration, and admin login. With dynamic menus, dropdowns, and interactive pages, Library Zone makes managing books and enhancing digital learning easy and efficient.
Library Zone is a simple web-based library management system that allows users to explore books, manage registrations, make payments, and provide feedback. It is built using HTML, CSS, JavaScript, and iframes to load different sections dynamically.
<img width="216" height="148" alt="image" src="https://github.com/user-attachments/assets/b2ab4dc5-e980-4de2-be2a-d8fb3e51510e" />

🚀 Features

Home Page – Welcomes users to the Library Zone.

Navigation Bar with Dropdowns – Provides quick access to different sections like Fiction, Non-Fiction, and E-Books.

Dynamic Breadcrumbs – Updates automatically as the user navigates.

Book Sections

Fiction (Wide range of fiction books)

Non-Fiction (Knowledge-rich collection)

E-Books (Digital resources)

User Authentication

Register new users

Login page for users

Admin login for administrators

Duration & Payment – Provides information about library membership duration and fee payment.

Feedback Form – Users can submit their feedback.

Contact Page – Displays contact information of the library.

🛠️ How It Works

The project runs on a single main page (index.html) which contains the navigation bar, logo, and iframe.

When a user clicks a menu item, the corresponding page is loaded into the iframe without refreshing the entire site.

Pages included:

home.html → Welcome page

ebooks.html → Lists available e-books

fiction.html → Fiction book collection

nonfiction.html → Non-fiction book collection

register.html → User registration form

login.html → Login form for users

admin.html → Simple admin login

duration.html → Membership duration info

payment.html → Payment details

contact.html → Contact information

feedback.html → Feedback submission form
<img width="612" height="408" alt="image" src="https://github.com/user-attachments/assets/40e25fe8-ff53-445d-901c-a17da882b925" />


📖 Managing Books

Since this is a basic front-end project, books are managed in static HTML pages:

Fiction, Non-Fiction, and E-Books pages contain book categories.

Each page can be extended to show book lists with details such as:

Title

Author

Availability (Available/Issued)

Borrow Duration

Future enhancement could include:

Adding localStorage / database to store books and users.

Adding an admin panel to manage book records (add, update, delete).

Integrating payment gateway APIs for real transactions.
<img width="174" height="148" alt="image" src="https://github.com/user-attachments/assets/c52b9fce-0c6f-45c6-bc66-57cd510a4e59" />


▶️ How to Run

Download or clone this repository.

Place all .html, css, and image files in the same project folder.

Open index.html in any modern browser.

Use the navigation menu to explore different sections.

📌 Example Workflow

User opens the site → Lands on Home Page.

Navigates to Books ▾ → Selects Fiction → Message appears “A wide range of books are available.”

Registers through Register Page → Logs in.

Views Duration & Payment details for membership.

Provides feedback using Feedback Form.

Admin can log in separately through Admin Page.

✨ That’s it! You now have a basic library management system prototype.
