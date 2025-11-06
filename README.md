
---

# 🐚 Unix Practical Questions – Directories & Files

**📅 Submission Date:** 25/08/2025
**💡 Topic:** Directories & Files Operations in UNIX
**🎯 Objective:** Practice file and directory manipulation commands in UNIX/Linux shell.

---

## 📂 Creating & Navigating

1. **Create a directory named `unix_practice` in your home directory**

   ```bash
   mkdir ~/unix_practice
   ```

   **Output:**
   *(No output — directory created successfully)*

   ---

2. **Navigate into `unix_practice`**

   ```bash
   cd ~/unix_practice
   ```

   **Output:**
   *(No output — prompt changes to indicate directory change)*

   ---

3. **Create two subdirectories named `docs` and `images`**

   ```bash
   mkdir docs images
   ```

   **Output:**
   *(No output — directories created successfully)*

   ---

4. **Check your current working directory**

   ```bash
   pwd
   ```

   **Output:**

   ```
   /home/username/unix_practice
   ```

   ---

5. **List all files and directories in the current directory, including hidden ones**

   ```bash
   ls -a
   ```

   **Output:**

   ```
   .  ..  docs  images
   ```

---

## 📄 File Creation & Editing

6. **Create three text files in `docs` named `a.txt`, `b.txt`, and `c.txt`**

   ```bash
   touch docs/a.txt docs/b.txt docs/c.txt
   ```

   **Output:**
   *(No output — files created successfully)*

   ---

7. **Write `"Welcome to Unix"` into `a.txt`**

   ```bash
   echo "Welcome to Unix" > docs/a.txt
   ```

   **Output:**
   *(No output — text written to file)*
   
   ---

8. **Append `"This is a practice session"` to `a.txt`**

   ```bash
   echo "This is a practice session" >> docs/a.txt
   ```

   **Output:**
   *(No output — line appended successfully)*
   
   ---

9. **Display the contents of `a.txt` on the screen**

   ```bash
   cat docs/a.txt
   ```

   **Output:**

   ```
   Welcome to Unix
   This is a practice session
   ```
   
   ---

10. **Count the number of words in `a.txt`**

    ```bash
    wc -w docs/a.txt
    ```

    **Output:**

    ```
    5 docs/a.txt
    ```

---

## 📁 Copying, Moving & Renaming

11. **Copy `a.txt` to a new file named `a_copy.txt` in the same folder**

    ```bash
    cp docs/a.txt docs/a_copy.txt
    ```

    **Output:**
    *(No output — file copied successfully)*
   
    ---

12. **Move `b.txt` to the `images` directory**

    ```bash
    mv docs/b.txt images/
    ```

    **Output:**
    *(No output — file moved successfully)*
   
    ---

13. **Rename `c.txt` to `notes.txt`**

    ```bash
    mv docs/c.txt docs/notes.txt
    ```

    **Output:**
    *(No output — file renamed successfully)*
   
    ---

14. **Copy all `.txt` files from `docs` to `unix_practice` directory**

    ```bash
    cp docs/*.txt .
    ```

    **Output:**
    *(No output — all text files copied successfully)*

---

## 🧹 Deleting & Cleaning Up

15. **Delete `a_copy.txt`**

    ```bash
    rm docs/a_copy.txt
    ```

    **Output:**
    *(No output — file deleted successfully)*
   
    ---

16. **Delete the entire `unix_practice` directory in one command**

    ```bash
    rm -r ~/unix_practice
    ```

    **Output:**
    *(No output — directory and contents deleted recursively)*

---


## ✅ Conclusion

This practical demonstrates core UNIX file and directory management commands such as `mkdir`, `cd`, `cp`, `mv`, `rm`, and `wc`. These commands are fundamental for efficient navigation and manipulation in a Linux/UNIX environment.

---
