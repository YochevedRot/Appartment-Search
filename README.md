<p align="center">
  <img src="images/logo.png" alt="Logo" width="30%" style="object-fit:cover;"/>
</p>

<h1 align="center">🏙️ Appartment Search</h1>

<p align="center">
  A modern full-stack web application for searching apartments for sale.<br/>
  Featuring a personalized dashboard with saved ads, published listings, user stats, and recent searches.
</p>

---

## 🏡 About The Project

**Appartment Search** is a responsive real estate search platform built for simplicity and speed.  
It enables users to find, save, and publish apartment listings through an intuitive and modern interface.

### ✨ Key Features
- 🔍 **Smart search** by keywords and filters (city, price, rooms, etc.)  
- ⭐ **Favorites system** — save listings for later  
- 📢 **Ad management** — post, edit, and delete your own listings  
- 👤 **Personal area** — manage your details and track statistics  
- 📊 **Recent searches** and user activity insights  
- ⚙️ **Clean full-stack architecture** — React + .NET Core + SQL Server  

---

## 🧩 Built With

- **Frontend:** ⚛️ React (Vite)  
- **Backend:** 🧱 .NET 8 Web API (C#) + Entity Framework Core  
- **Database:** 🗄️ SQL Server  
- **Authentication:** 🔐 JWT Tokens  

---

## 🖼️ Screenshots

| Home Page | Apartment Details | Personal Area |
|------------|------------------|----------------|
| ![Home Page](images/homePage.png) | ![Details](images/details.png) | ![Personal Area](images/personalArea.png) |

<p align="center">
  <a href="https://github.com/YochevedRot/appartment-search/tree/main/images">📸 View More Screenshots</a>
</p>

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/appartment-search.git
cd appartment-search
```
#### 2️⃣ Install client dependencies and run
```bash
cd AppartmentSearch-Client
npm install
npm run dev
```
#### 3️⃣ Setup and run the server
```bash
cd ../AppartmentSearch-Server
dotnet restore
dotnet build
```
#### 4️⃣ Configure the database
If migrations already exist:
```bash
dotnet ef database update
```
If not:
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```
Make sure your appsettings.json includes a valid connection string:
```bash
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\\\mssqllocaldb;Database=AppartmentSearchDb;Trusted_Connection=True;MultipleActiveResultSets=true"
  }
}
```
#### 5️⃣ Run the server
```bash
dotnet run
```

---

#### 🧭 Usage

- 🌐 Open [http://localhost:5173](http://localhost:5173)  
- 🔐 Sign up or log in to your account  
- 🏙️ Search apartments by city, price range, and filters  
- ⭐ Save or 📢 publish listings  
- 👤 Access your personal dashboard to manage data and view stats  


---

#### 🔒 License

This project is private and may not be copied, modified, or redistributed without explicit permission from the author.

<p align="center"> Made with ❤️ by <a href="https://github.com/YochevedRot">Yocheved Rot</a> </p> 
