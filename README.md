# 🏦 Banker's Algorithm Web App

This project is a **web-based implementation of the Banker's Algorithm**, a classic algorithm used in operating systems for **deadlock avoidance** in resource allocation.

---

## 📌 Features

- Input number of processes and resource types  
- Automatically generate input fields or use default sample data  
- Enter maximum demand and allocation matrices  
- Check if the system is in a safe state  
- Process resource requests dynamically  
- Get instant feedback and safe sequence (if applicable)

---

## 🌐 Live Demo

You can run this app locally by opening `index.html` in a browser.

---

## 🛠️ How to Use

1. Enter the number of processes and resources at the top of the page.
2. Click **"Generate Input Fields"** to create input fields for Max and Allocation matrices.
3. Optionally, use default values by simply loading the page (they load automatically).
4. Click **"Check Safe State"** to verify if the system is in a safe state.
5. If safe, a resource request section will appear:
    - Enter a process number and a request vector (e.g., `1,0,2`)
    - Click **"Process Request"** to check if it can be safely granted.

---

## 📋 Sample Default Data

- **Processes**: `5`  
- **Resources**: `3`  
- **Available**: `3,3,2`  

**Max Matrix:**

P0: 7,5,3
P1: 3,2,2
P2: 9,0,2
P3: 2,2,2
P4: 4,3,3

**Allocated Matrix:**

P0: 0,1,0
P1: 2,0,0
P2: 3,0,2
P3: 2,1,1
P4: 0,0,2

---

## 📂 Project Structure

. ├── index.html # Main HTML file
├── style.css # (Optional) CSS styling file


---

## 💡 Technologies Used

- HTML5  
- JavaScript (Vanilla)  
- (Optional) CSS3

---

## 🧠 What is the Banker's Algorithm?

Banker's Algorithm is used to allocate resources to processes in a way that **avoids deadlocks**.  
It checks if the system will remain in a **safe state** after allocating requested resources to a process.

---

## 📜 License

This project is **open-source** and free to use.



