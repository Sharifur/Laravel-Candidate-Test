# Test Project For Laravel Candidate# Laravel Candidate Test

## Overview

This test is designed to assess your skills in Laravel backend development and frontend integration using modern tools. You are required to implement the functionality based on the attached design image using the tech stack outlined below.

## Tech Stack Requirements

Please use the following technologies to complete the test:

1. **Backend:**
   - **Laravel** for creating APIs (no authentication required).
   - Use **Laravel Resource** for API responses.
   - Use **Laravel Request** for validation of API inputs.

2. **Frontend:**
   - **Next.js (14)** as the frontend framework.
   - **Shadcn** (UI library): You should use this for building the UI components. (https://ui.shadcn.com/)
   - **Zustand** as the state management solution. (https://zustand-demo.pmnd.rs/)
   - **Zod** for validating the form in Next.js. (https://zod.dev/)
   - **Tailwind CSS** for styling.

3. **Other Notes:**
   - Use **Typescript** for both backend and frontend development.
   - Implement a **normal HTML table** instead of Shadcn's Tanstack Table for listing data (as Shadcn's table uses Tanstack Data Table, which you should not use).

## Requirements

1. **API Development (Laravel):**
   - Create a simple API to handle CRUD operations based on the attached design.
   - Use **Laravel Request** classes for input validation.
   - Return responses using **Laravel Resource** classes for structured API responses.

2. **Frontend Development (Next.js + Shadcn UI):**
   - Set up a **Next.js** frontend.
   - Use **Shadcn UI** components where appropriate, except for the data table.
   - Use **Zustand** to manage the state for the application.
   - Use **Zod** to handle frontend form validation.
   - Use a **normal HTML table** to display data (instead of Shadcn's default table).

3. **Styling (Tailwind CSS):**
   - Apply **Tailwind CSS** for custom styles as needed.
   - Ensure the layout matches the design in the provided image.

## Setup Instructions

### Backend (Laravel)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

## Submission

1. Fork this repository.
2. Create a new branch for your solution.
3. Implement the project as described above.
4. Push your code to your forked repository.
5. Submit a pull request with a description of your implementation.

## Evaluation Criteria

- Proper use of **Laravel Resources** and **Requests** for APIs.
- Clean and well-structured **Next.js** implementation.
- Correct use of **Shadcn UI** and **Zustand**.
- Efficient use of **Typescript** for both backend and frontend.
- Responsive and well-styled UI using **Tailwind CSS**.
- Proper form validation using **Zod** in **Next.js**.
- Adherence to the attached design image.
