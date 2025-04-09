# Angular Basics – Learning Journal ❤️

Welcome! This repository contains a project I developed while studying Angular through the **Angular Basics course from Simplilearn**. It represents a hands-on learning journey focusing on **Angular Forms**, **Services**, and other core concepts of the framework.

## 🚀 About the Project

This Angular project demonstrates how to create a user registration form using **Template-Driven Forms**, including data validation and submission logic.

The form allows:

- Capturing and validating user data
- Real-time feedback with error messages
- Integration with a `submit()` function

Additionally, I learned how to:

- Create and register **components**
- Import essential modules like `FormsModule`
- Create and use **Angular Services** with `@Injectable`

---

## ❤️ Learning Summary
A detailed summary of the key concepts covered is available in the following file:

> 📌 [`/Angular_Learning_Journal2.0.pdf`](./Angular_Learning_Journal2.0.pdf)  
> Includes explanations of Template-driven vs Reactive Forms, FormControl, FormGroup, Services, and more.

---

## Technologies and Resources Used

- Angular CLI
- Template-Driven Forms
- Angular Services
- Bootstrap for layout and styles
- `FormsModule` and `CommonModule`

---

## How to Run

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
ng serve
```
Then open http://localhost:4200 in your browser.

## Useful Commands
ng new democomponents – Creates a new Angular project
ng g c form-component – Generates a new form component
ng g service data – Creates a new service for business logic

## Notes
Make sure to import FormsModule in the @Component or @NgModule where you're using ngModel.
When displaying validation errors, use ?.['errorName'] to avoid compiler warnings.

---
Made with ❤️ while learning Angular through the Simplilearn – Angular Basics course.
