# 🗳️ Poll System - ASP.NET MVC Project

A web-based Poll System developed using ASP.NET MVC that allows users to create, vote, and view results of polls in real-time. Designed with scalability and usability in mind, this project demonstrates key concepts such as CRUD operations, user authentication, and chart-based result visualization.

---

## 🚀 Features

- ✅ Create polls with multiple options
- ✅ Vote on available polls (once per user/IP)
- ✅ View poll results with percentage-based charts
- ✅ Admin panel to manage polls and results
- ✅ User authentication and authorization
- ✅ Responsive UI with Bootstrap

---

## 🛠️ Tech Stack

- **Backend:** ASP.NET MVC 5 (.NET Framework)
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Database:** SQL Server / LocalDB
- **ORM:** Entity Framework
- **Authentication:** ASP.NET Identity

---

## 📸 Screenshots

*(Add screenshots of poll creation, voting page, and results chart here)*

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/poll-system-mvc.git
cd poll-system-mvc
```

2. **Open in Visual Studio 2013**

   - Open the `.sln` file in Visual Studio.

3. **Configure the Database**

   - Update the connection string in `Web.config`.

```xml
<connectionStrings>
  <add name="DefaultConnection" connectionString="Your_Connection_String" providerName="System.Data.SqlClient" />
</connectionStrings>
```

4. **Apply Migrations**

   - Open **Package Manager Console** and run:

```powershell
Update-Database
```

5. **Run the Project**

   - Press `F5` or click **Start** to launch in your browser.

---

## 👤 Admin Access

- **Username:** `admin@example.com`
- **Password:** `Admin@123`

*(You can change this in the database if needed)*

---

## 📁 Folder Structure

```
/Controllers     --> MVC Controllers
/Models          --> Data models
/Views           --> Razor Views
/Scripts         --> JS scripts
/Content         --> CSS & assets
/App_Start       --> RouteConfig, FilterConfig etc.
```

---

## 🧪 Future Improvements

- Add support for user comments on polls
- Add poll expiry time and scheduling
- Real-time updates with SignalR
- Export results as PDF/CSV

---

## 📄 License

MIT License - feel free to use and modify.

---

## 🤝 Contributing

Pull requests and suggestions are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

Developed by OkSoftSystems – henryforjobs2024@gmail.com

Project Link: https://github.com/OkSoftSystems/ASP.NetMVC-PollSystem