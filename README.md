
# ProjectPOE (Part 1)

**Student Name:** Gift Ndlovu  
**Student ID:** ST10537076  
**Repository:** `ndlovugift/ProjectPOE`  
**IDE:** Apache NetBeans  
**Testing Framework:** JUnit 5  

---

## Project Overview
This Java application manages user registration, credential validation, and login authentication. It provides standard console prompts and features rigorous validation rules to ensure data formatting compliance prior to account creation.

---

## Features & Validation Criteria

* **Username Check (`checkUserName`):**
  * Must contain an underscore (`_`).
  * Must not exceed **5 characters** in length.

* **Password Complexity (`checkPasswordComplexity`):**
  * Must be at least **8 characters** long.
  * Must contain at least **one uppercase letter**.
  * Must contain at least **one number**.
  * Must contain at least **one special character**.

* **Cell Phone Number (`checkCellPhoneNumber`):**
  * Must follow the South African international format (e.g., `+27831234567`).

* **Authentication (`loginUser` & `returnLoginStatus`):**
  * Validates entered credentials against registered details using `.equals()`.
  * Returns formatted welcome and error messages based on authentication outcomes.

---

## Project Structure
## Running the Application

### 1. Execute Application Console
1. Open the project in **Apache NetBeans**.
2. Locate `Login.java` under `Source Packages -> Login`.
3. Press **`Shift + F6`** (or right-click `Login.java` $\rightarrow$ **Run File**).
4. Follow the registration and login prompts in the Output window.

### 2. Run Unit Tests
1. Locate `LoginTest.java` under `Test Packages -> Login`.
2. Press **`Alt + F6`** (or right-click `LoginTest.java` $\rightarrow$ **Test File**).
3. View the test assertions inside the **Test Results** window.
