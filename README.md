# 2025-ITELEC2-LAB008
Week 04 - Conditional Statements

Laboratory # 08 - Guided Coding Exercise: Simple if Statement in Python

## **Instructions**

### **Step 1.1: Accept the Assignment**

   1. Click on the assignment link provided by your instructor.
   2. GitHub Classroom will create a **private repository** under your GitHub account.
   3. After the repository is created, click **"Go to Repository"** to view your assignment.

---

### **Step 1.2: Setup your Git Environment**
Only perform this if this is the first time you will setup your Git Environment

   1. Create a GitHub Account:
   ```bash
   https://github.com/signup?source=login
   ```
      
   2. Download and Install Git on your Laptop/Desktop:
   ```bash
   https://git-scm.com/downloads
   ```
   
   3. Create a Folder in your Laptop/Desktop
   4. Right-click anywhere in the created folder and select "Open Git Bash Here".
   5. In the Git Bash Terminal, set your git name, perform command:
   ```bash
   git config --global user.name "Your Name"
   ```
   
   6. In the Git Bash Terminal, set your git email, perform command:
   ```bash
   git config --global user.email "your.email@example.com"
   ```
   
   7. Create your SSH Key, just follow the instructions, no need to provide filename and passphrase. In the Git Bash Terminal, perform command:
   ```bash
   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
   ```
   
   8. Copy your SSH Keys into clipboard. In the Git Bash Terminal, perform command:
   ```bash
   clip < ~/.ssh/id_rsa.pub
   ```
   
   9. Log in to your GitHub account.
   10. In the upper-right corner of GitHub, click your profile picture and select Settings.
   11. In the left sidebar, click on SSH and GPG keys.
   12. Click the New SSH key button.
   13. In the Title field, give the key a recognizable name (e.g., "My Windows Laptop").
   14. In the Key field, CTRL + V or paste the keys copied into your clipboard. Save the key.
   15. Go Back to terminal, use command:
   ```bash
   ssh -T git@github.com
   ```

### **Step 2: Clone the Repository to Your Local Machine**

   1. On your repository page, click the green **"Code"** button.
   2. Copy the repository URL (choose HTTPS for simplicity).
   3. Open your terminal (or Git Bash, Command Prompt, or PowerShell) and run:
   
   ```bash
   git clone <git_repo_url>
   ```
   
   4. Navigate into the cloned folder:
   
   ```bash
   cd <git_cloned_folder>
   ```

### **Step 3: Complete the Assignment**

**Laboratory # 08 - Guided Coding Exercise: Simple if Statement in Python**

   **Objective:**
   - Understand the syntax and structure of a basic if statement.
   - Learn how a condition controls the execution of a code block.
   - Practice using comparison operators in conditional statements.
   - Understand the importance of indentation in Python.

   **Desired Output (Example 1):**
   ```bash
   It's a hot day!
   
   ```

   **Desired Output (Example 2):***(No output)*
   
   - (Example 1) - If temperature is greater than 30.
   - (Example 2) - If temperature is 30 or less.
      
   **Notable Observations (to be discussed after completing the exercise):**
   - The code inside the if statement block only executes if the condition is True.
   - Indentation is crucial in Python. It defines the code block associated with the if statement. Incorrect indentation will lead to errors.
   - The `>` operator is used for "greater than" comparison. Other comparison operators include: 
      - `<` (less than)
      - `>=` (greater than or equal to)
      - `<=` (less than or equal to)
      - `==` (equal to)
      - `!=` (not equal to)
   - Variables can be used in the condition. This makes the if statement dynamic.

   **Python Best Practices**
   - Descriptive Variable Names: Use clear and descriptive variable names (e.g., temperature instead of t). This improves code readability.
   - Comments: Add comments to explain your code's logic, especially for more complex conditions.
   - Consistent Indentation: Maintain consistent indentation (4 spaces per level is the recommended standard in Python). This is essential for Python's syntax.
   - Meaningful Conditions: Write conditions that are clear and easy to understand.
   - Test Thoroughly: Test your code with different inputs to ensure it behaves as expected in various scenarios (e.g., when the condition is true and when it's false).

   **Step-by-Step Instructions:**

   1. Setting up: Open your preferred Python environment or Text Editor, and create a Python Script.
      - Required Filename: `if_statement_basic.py`
      
   2.  Define a variable:
      - Create a variable named temperature. Assign it a numeric value (e.g., 35). You can change this value later to test different scenarios.
```python
temperature = 35  # Or any other number
```
      
   3.  Write an if statement:
      - Use the if keyword followed by a condition. The condition should check if temperature is greater than 30. End the line with a colon (:).
```python
if temperature > 30:
```

   4. Print a message (indented)
      - On the next line, indented, write the code that you want to execute if the condition is true. In this case, print the message "It's a hot day!". Make sure the indentation is consistent (4 spaces).
```python
    print("It's a hot day!")  # Indented 4 spaces
```

   5. Complete Code: Combine the steps above to form the complete program.

   6. Run the code: Execute your Python code.
   7. Observe the output: 
      - If temperature is greater than 30, you should see the message printed.
      - If temperature is 30 or less, nothing will be printed.
     
   8. Experiment: Change the value of temperature and run the code again. Try values greater than 30 and values less than or equal to 30. Observe the different outputs.

   9. Try other comparison operators: Change the > operator to other comparison operators (e.g., <, >=, <=, ==, !=) and see how the program's behavior changes. For example, try: if temperature <= 30:

   **Conclusion**
   This exercise introduced the fundamental concept of the if statement in Python. You learned how to write a simple if statement, how a condition controls the execution of code, and the importance of indentation. You also practiced using comparison operators and following Python best practices. The if statement is a powerful tool for creating programs that can make decisions based on different conditions. This is a building block for more complex control flow structures you'll learn later.

### **Step 4: Push Changes to GitHub**
Once you've completed your changes, follow these steps to upload your work to your GitHub repository.

1. Check the status of your changes:
   Open the terminal and run:
   
```bash
git status
```
   This command shows any modified or new files.
   
2. Stage the changes:
   Add all modified files to staging:
   
```bash
git add .
```
   
3. Commit your changes:
   Write a meaningful commit message:
   
```bash
git commit -m "Submitting Python Week 04 - Laboratory # 08"
```
   
4. Push your changes to GitHub:
   Upload your changes to your remote repository:
   
```bash
git push origin main
```
