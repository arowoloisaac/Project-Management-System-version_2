# Project Management System Version_2
An API of the **Project Management System version 2** built to help individuals and organizations efficiently manage projects, tasks, and collaboration. It allows users to create projects, assign tasks and subtasks, manage roles, and track progress in real-time.  [link to version 1](https://github.com/arowoloisaac/Project-Management)


## 🚀 Features  

- 🔑 Role-based authentication & authorization  
- 🏢 Support for both personal and organizational projects  
- 📂 Project, task, and sub-task management  
- 👥 User & team collaboration  
- ⏰ Google Calendar integration for reminders & due dates (optional)  
- 📊 Dashboard with progress tracking  
- ⚡ Built with scalability and microservices in mind  


## 🛠️ Tech Stack  

- **Backend:** .NET 9 (Web API, ASP.NET Core Identity, Quartz for background jobs)  
- **Database:** MSSQL  
- **Containerization:** Docker  
- **Other Integrations:** Google Calendar API, role-based contextual system  


## 📦 Installation  

### Prerequisites  
- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- [MSSQL](https://www.microsoft.com/en-us/sql-server)  
- [Docker](https://www.docker.com/) (optional, for containerization)  

### Steps  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/project-management-system-version_2.git
   cd project-management-system
   cd backend
   dotnet restore
   dotnet run
   ```

2. Access the application at:
   ```bash
   https://localhost:[port]/swagger

   or
   https://localhost:[port]/scalar
   ```

   
## 🏗️ System Architecture

This section shows the high-level architecture of the system.


## 📖 Usage

- Register/Login as a user
- Create or join an organization
- Create projects and assign roles (Admin, Manager, Member, etc.)
- Add tasks & subtasks
- Track progress via dashboard
- (Optional) Sync with Google Calendar for reminders


##🤝 Contributing

### Contributions are welcome!
- Fork the repo
- Create your feature branch (git checkout -b feature/amazing-feature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
- Open a Pull Request
- Please ensure that your code passes tests and follows the existing style.
