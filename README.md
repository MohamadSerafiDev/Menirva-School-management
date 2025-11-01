# Menirva School Management System

A comprehensive Flutter-based school management system that provides different interfaces and functionalities for various roles within the educational institution.

## 🚀 Technologies & Architecture

-   **Framework:** Flutter 3.8+
-   **State Management:** Flutter Bloc & GetX
-   **Architecture:** MVC (Model-View-Controller)
-   **Authentication:** Local Auth & PIN-based security
-   **Localization:** Multi-language support (Arabic/English)
-   **Backend Integration:** RESTful API using HTTP package
-   **UI Components:** Material Design & Custom Widgets

## 📦 Main Packages

-   **State Management**

    -   `flutter_bloc`: ^9.1.1 - For robust state management
    -   `get`: ^4.7.2 - For navigation and dependency injection

-   **UI/UX**

    -   `google_fonts`: ^6.2.1 - For custom typography
    -   `flutter_svg`: ^2.1.0 - For SVG asset handling
    -   `carousel_slider`: ^5.1.1 - For image sliders
    -   `salomon_bottom_bar`: ^3.3.2 - For bottom navigation
    -   `smooth_page_indicator`: ^1.2.1 - For page indicators

-   **Authentication & Security**

    -   `local_auth`: ^2.3.0 - For biometric authentication
    -   `pinput`: ^5.0.1 - For PIN input fields

-   **Utilities**
    -   `shared_preferences`: ^2.5.3 - For local storage
    -   `translator`: ^1.0.3+1 - For text translation
    -   `timeago`: ^3.7.1 - For time formatting
    -   `firebase_messaging`: ^16.0.0 - For push notifications

## 🎯 Key Features

-   Multi-role user system (Student, Teacher, Librarian, Nurse)
-   Biometric authentication
-   Multi-language support
-   Event management system
-   Library management system
-   Complaint management system
-   Push notifications
-   File sharing capabilities
-   Profile management

## 📱 User Interface

### Student Role

| Feature    | Description                                 | Screenshot                                                                                                                           |
| ---------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Home Page  | Dashboard with quick access to all features | [English](screenshots/student/student%20home%20page%20english.png), [Arabic](screenshots/student/student%20home%20page%20arabic.png) |
| Profile    | Student profile management                  | [View](screenshots/student/student%20profile.png)                                                                                    |
| Schedule   | Weekly class schedule                       | [View](screenshots/student/student-weekly%20schedule.png)                                                                            |
| Books      | Browse and borrow library books             | [Browse](screenshots/student/student-books%20page.png), [Borrow](screenshots/student/student-borrow%20book.png)                      |
| Events     | View and interact with school events        | [List](screenshots/student/student-events.png), [Comments](screenshots/student/student-event%20commant.png)                          |
| Complaints | Submit and track complaints                 | [New](screenshots/student/student%20complain.png), [Previous](screenshots/student/student%20pre%20complaint.png)                     |

### Librarian Role

| Feature    | Description                           | Screenshot                                                                                                                                                                                            |
| ---------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Home       | Main dashboard for library management | [View](screenshots/librarian/librarian-main%20home.png)                                                                                                                                               |
| Books      | Manage book inventory                 | [List](screenshots/librarian/librarian-books.png), [Details](screenshots/librarian/librarian-book%20details.png)                                                                                      |
| Add Books  | Add new books to library              | [Empty](screenshots/librarian/librarian%20-add%20book.png), [Filled](screenshots/librarian/librarian-add%20book%20filled.png)                                                                         |
| Borrows    | Manage book borrowing requests        | [Pending](screenshots/librarian/librarian-pending%20borrows.png), [Accepted](screenshots/librarian/librarian-accepted%20borrows.png), [Rejected](screenshots/student/libraian-rejected%20borrows.png) |
| Complaints | Handle library-related complaints     | [View](screenshots/librarian/librarian-complaint.png), [Edit](screenshots/librarian/librarian-edit%20complaint.png), [Save](screenshots/librarian/librarian-save%20complaint.png)                     |

## 🛠 Setup & Installation

1. Clone the repository
2. Ensure Flutter 3.8+ is installed
3. Run `flutter pub get` to install dependencies
4. Configure your environment variables
5. Run the application using `flutter run`

## 🌐 Supported Platforms

-   Android
-   iOS
-   Web
-   Linux
-   Windows
-   macOS

## 📄 License

This project is licensed under the MIT License, which allows you to:

-   ✔️ Use the software for commercial purposes
-   ✔️ Modify the source code
-   ✔️ Distribute the software
-   ✔️ Use and modify the software privately

The only requirement is to include the original copyright notice and license in any copy of the software/source.

See the [LICENSE](LICENSE) file for the full license text.
