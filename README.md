# 🎮 Lang Lá Game (Java + MySQL)

An improved MMORPG fan project inspired by the Naruto world, built with **Java** and **MySQL**.  
Originally based on an open-source Java version, this project has been **heavily customized and expanded** with new gameplay systems, events, and database integration.

---

## 🌿 Overview
This project represents a complete **client–server game** written in Java, connected to a **MySQL database (via XAMPP)** for player accounts, levels, and item storage.

The system supports:
- Custom character skins (cải trang)
- Special events (sự kiện)
- Item shop system (shop vật phẩm)
- Real-time data saving via MySQL

---

## 💡 Features

### 🕹️ Gameplay
- 🧍 Character creation and login system  
- ⚔️ Battle and skill effects  
- 🏕️ Map & teleport system  
- 🧥 **Cải trang** feature (custom skin transformation)
- 🎉 **Sự kiện** system (temporary events like Halloween, New Year)
- 🛒 **Shop vật phẩm** (item purchase using in-game or recharge currency)

### 🗄️ Server & Database
- Java server handles player sessions and game logic  
- MySQL stores account info, inventory, levels, and currencies  
- XAMPP provides local host management (Apache + MySQL)

### 🧩 Client
- Built with **LibGDX**  
- Connects via socket (port 2907)  
- Supports desktop launcher & Android APK  

---

## 🧰 Technologies
| Component | Description |
|------------|-------------|
| **Language** | Java 17+ |
| **Database** | MySQL (via JDBC) |
| **Framework** | LibGDX |
| **Server** | Custom socket-based server |
| **Tools** | NetBeans / VS Code / XAMPP |

---

## ⚙️ Run Locally

### 🧩 Requirements
- JDK 18+  
- XAMPP (Apache + MySQL)  
- Database file: `langla.sql`

---

### 🪜 Steps
1. Import `langla.sql` into **phpMyAdmin**.  
2. Start **MySQL** and **Apache** in XAMPP.  
3. Run the **server**:
   ```bash
   java -cp "target\classes;lib\*" com.sg188.server.Main
Run the client:

bash
Sao chép mã
java -jar LangLaClient.jar
Login with:

makefile
Sao chép mã
Username: thanhduy01
Password: sdt0344
📦 Download Project
Because this project includes full game assets (client, server, and database),
please download it from Google Drive:

➡ Download LangLa-Game.zip (Google Drive)

🎥 Demo Video
Watch how the client connects to the server and interacts with MySQL database:

▶️ Watch Demo on Google Drive / YouTube

🧠 Key Improvements from Original Source
Rebuilt UI and client connection logic

Added Cải trang system (dynamic outfit switching)

Added Event Manager (holiday and special event system)

Added Shop System synced with database

Optimized saving/loading through MySQL

Integrated AutoPro and SettingsTab for smoother automation

🧑‍💻 Author
Nguyen Thanh Duy
📧 duynguyen.codes@gmail.com
🌐 github.com/dev-duynguyen
