# RebarPro  - Civil engineering software solutions

**RebarPro** is an desktop application designed to simplify iron bar inventory management for civil engineering projects. It helps engineers reduce material wastage, optimize resource allocation, and streamline inventory tracking for efficient project execution.

By centralizing iron bar data, **RebarPro** enables real-time updates on stock levels, usage, and remaining materials, empowering users to make informed decisions that cut costs and improve project efficiency. Whether for small construction sites or large-scale infrastructure projects, it provides an intuitive interface for easy management of inventories.

Built with modern technologies like **React**, **Vite**, **TailwindCSS**, and **Electron.js**, **RebarPro** offers a fast, responsive, and cross-platform solution that works seamlessly across Windows, macOS, and Linux. The backend leverages **SQLite (better-sqlite3)** for reliable data storage, while secure user authentication powered by **Clerk** and automatic updates via **electron-updater** ensure smooth, secure operations.

In essence, **RebarPro** is a powerful tool that transforms inventory management, reduces human error, and enhances overall project efficiency in civil engineering.


---

## Features  

### 1. **Inventory Management**  
- Add, update, and track iron stocks/inventory.  
- Calculate usage and minimize wastage efficiently.  

### 2. **User Authentication**  
- Secure authentication powered by [Clerk](https://clerk.dev/). 

### 3. **Modern User Interface**  
- Clean and responsive design using **React** and **TailwindCSS**.  
- Rich components and icons powered by **Ant Design (antd)**.  

### 4. **Auto Updates**  
- Automatic updates powered by [electron-updater](https://www.electron.build/auto-update/).  
- Seamless integration with GitHub Releases ensures users always have the latest version.  

### 5. **Lightweight and Efficient Database**  
- Built-in data storage using **SQLite (better-sqlite3)** for fast and reliable data handling.  

### 6. **Cross-Platform Compatibility**  
- Available for Windows, macOS, and Linux.  

---

## Technologies Used  

### **Frontend**  
- **React** with Vite: Lightning-fast build system and development environment.  
- **TailwindCSS**: Utility-first styling for a sleek and responsive UI.  
- **Ant Design (antd)**: Ready-to-use, customizable React components.  

### **Backend**  
- **Electron.js**: Framework for creating cross-platform desktop applications using web technologies.  
- **SQLite (better-sqlite3)**: Embedded database for efficient and secure data management.  

### **Authentication**  
- **Clerk**: Simple and powerful authentication solution.  

### **Auto-Updater**  
- **electron-updater**: Automatically delivers updates via GitHub Releases.  

---

## App Interface  

### 1. **Home Page / Stock List**  
![Screenshot 2024-12-09 221351](https://github.com/user-attachments/assets/343d8d47-46c2-4e91-b46e-cab015476e8f)  

### 2. **Cut List**  
![Screenshot 2024-12-10 154308](https://github.com/user-attachments/assets/7c98ec6a-cc14-4a4c-939a-becf6158fce4)  

### 3. **Balance List**  
![Screenshot 2024-12-10 154336](https://github.com/user-attachments/assets/d7522f8f-e846-4e21-9dba-a89dfee625d5)  

### 4. **Scrap List**  
![Screenshot 2024-12-10 154420](https://github.com/user-attachments/assets/b0b3597b-20a0-4bd4-ad8e-a1044b6db95c)  

### 5. **About**  
![Screenshot 2024-12-09 221413](https://github.com/user-attachments/assets/a1aba86a-bc89-4c99-aeb4-a84ed036ca26)  

### 6. **Account**  
![Screenshot 2024-12-09 221428](https://github.com/user-attachments/assets/7a3da917-2cba-4db8-b122-5e3345702be0)  


---

## Installation  

### Prerequisites  
- Node.js (v18+ recommended).  
- Git installed on your system.  

### Steps  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/Shismohammad/RebarPro.git  
   cd RebarPro  
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   ```  

3. Start the development server:  
   ```bash  
   npm run dev  
   ```  

4. Build the application:  
   ```bash  
   npm run build  
   ```  

5. Package the app

   ```bash
   npm run dist
   ```

6. Step 4 and 5 combined for windows

   ```bash
   npm run build:win
   ```

---


## License  

This project is proprietary software. All rights are reserved by the author. You may not modify, distribute, or use this software without explicit written permission from the author.  

