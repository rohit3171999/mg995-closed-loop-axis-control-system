# 🤝 Contributing Guidelines

Welcome to the **MG995 Closed-Loop Axis Control System** repository.

This project follows structured Git workflows and professional documentation standards.  
All contributors (students) must follow the guidelines below to ensure consistency and maintain quality.

---

# 📌 1. Contribution Workflow

Please follow this step-by-step workflow:

1. Accept the GitHub Classroom assignment.
2. Clone your assigned repository locally.
3. Create meaningful commits while working.
4. Push changes regularly.
5. Ensure your code compiles successfully before final submission.

---

# 🧾 2. Commit Message Format (Mandatory)

This repository follows a structured commit convention inspired by **Conventional Commits**.

## ✅ Format


## 🔹 Allowed Commit Types

- `feat:` → Adding a new feature  
- `fix:` → Fixing a bug  
- `docs:` → Documentation updates  
- `refactor:` → Code restructuring (no functionality change)  
- `style:` → Formatting changes (indentation, spacing)  
- `test:` → Testing-related updates  


❗ Commits like `update`, `changes`, `final`, `done` are NOT allowed.

---

# 📚 3. Documentation Requirements (Doxygen Mandatory)

All submissions must include proper Doxygen documentation.

## 🔹 File-Level Documentation Required

Each `.ino` file must include:

- `@file`
- `@brief`
- `@author`
- `@date`
- `@details`

Example:

```cpp
/**
 * @file main.ino
 * @brief MG995 Closed-Loop Axis Control System
 * @author YOUR_NAME
 * @date YYYY-MM-DD
 *
 * @details
 * Implements PWM-based closed-loop control for MG995 servo motor.
 */

---



