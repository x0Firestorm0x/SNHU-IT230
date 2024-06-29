# SNHU-IT230

Summary of Requirements and Goals

The application developed enables students to register for courses for a term of study, ensuring adherence to specific business rules:

  - Each course carries three credit hours.
  - A student can register for a maximum of three courses (nine credit hours).
  - No duplicate course registrations are allowed.
  - The application must validate user input, display registration confirmation or error messages, and update the total credit hours.

The console application aimed to output a list of courses, while the WPF application provided a graphical user interface for course registration.
What I Did Particularly Well

  - Code Refactoring: I efficiently refactored the initial code to use arrays for better manageability and readability.
  - UI Design: The WPF application was designed with a user-friendly interface, ensuring clear feedback and intuitive course registration.
  - Validation Logic: Implemented robust validation to ensure adherence to business rules, preventing duplicate registrations and credit hour overages.

Console vs. WPF Application Designs

  Console Application:
      - Focused on listing courses using arrays and loops for simplicity and clarity.
      - User interaction was minimal, as it mainly printed course names to the console.

  WPF Application:
      - Designed with interactive UI components (ComboBox, ListBox, TextBox, Button) to facilitate course registration.
      - The interface provided immediate feedback and displayed error or confirmation messages directly in the application window.
      - The UI design considered user experience by providing clear instructions, intuitive controls, and real-time feedback.

User-Centered UI Design:

  - Screens and Features: The WPF application included screens for course selection and a list of registered courses, supporting dynamic updates based on user actions.
  - Successful Design: By focusing on ease of use and immediate feedback, the design ensured that users could easily navigate the application and understand their registration status.

Approach to Debugging and Coding

  - Systematic Debugging: Used a methodical approach to identify and fix syntax and logical errors, ensuring the code compiles and runs correctly.
  - Code Refactoring: Simplified the code by using arrays and loops, making it more readable and maintainable.
  - Testing: Regularly tested the application to validate functionality and ensure adherence to requirements.

Techniques and Strategies:

  - Step-by-Step Debugging: Addressed issues one at a time, ensuring each part of the code worked before moving on.
  - Refactoring: Continuously improved the code structure for better performance and readability.
  - Testing: Frequent testing ensured that new changes did not introduce new bugs.

These strategies can be applied in future projects to systematically debug, refactor, and test code for better software development practices.
Innovation and Overcoming Challenges

  - UI Feedback Mechanism: Replacing MessageBox with a TextBlock for inline error and confirmation messages was an innovative solution to provide a seamless user experience.
  - Array Utilization: Transitioning from individual course objects to an array of courses improved code efficiency and scalability.
  - Validation Logic: Implementing comprehensive validation logic to enforce business rules required innovative thinking to ensure all scenarios were handled correctly.

By focusing on these areas, the application not only met user needs but also adhered to best practices in software development, providing a robust and user-friendly solution for course registration.
