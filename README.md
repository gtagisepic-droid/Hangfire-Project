# 🚀 Hangfire-Project - Automate Recurring Tasks Without Coding

[![Download Hangfire-Project](https://img.shields.io/badge/Download-Now-ff6b6b?style=for-the-badge&logo=github&logoColor=white&labelColor=4ecdc4)](https://github.com/gtagisepic-droid/Hangfire-Project/releases)

Hangfire-Project is a ready-to-use application that runs scheduled background jobs on your Windows computer. It stores job information in a SQL Server database and provides a secure dashboard to monitor everything. No programming knowledge required.

## 🚀 Getting Started

This guide helps you download and start using Hangfire-Project on a Windows PC. You do not need to be a programmer. The application handles recurring tasks automatically, such as sending emails, cleaning up files, or generating reports on a schedule. It uses a protected dashboard so you can see what is happening at any time.

## 📥 Download and Install

Visit this link to download the application: [Download Hangfire-Project](https://github.com/gtagisepic-droid/Hangfire-Project/releases). The download page will show you the latest version available for Windows. After you have the file, you can run the application on your computer.

## ✨ Key Features

- **Automatic job discovery** – The application finds and runs scheduled tasks without manual setup.
- **Recurring jobs** – Set tasks to repeat daily, weekly, or at any interval you choose.
- **Named queues** – Organize jobs into separate queues so important tasks get priority.
- **Protected dashboard** – A secure web page shows job status, history, and errors. Only authorized users can access it.
- **SQL Server storage** – All job details are saved in a Microsoft SQL Server database, so nothing is lost if the computer restarts.
- **Swagger API documentation** – Test and explore the application’s built-in web services through a simple interface.
- **Windows-friendly** – Runs as a background service on Windows 10 or later.

## 🖥️ System Requirements

- Windows 10 or Windows 11 (64-bit)
- .NET 10 runtime (free download from Microsoft)
- Microsoft SQL Server (any edition, including the free Express edition)
- 4 GB of RAM or more
- 1 GB of free disk space
- A modern web browser (Chrome, Edge, or Firefox) for the dashboard

## 🛠️ How to Use

After the application is running, open your web browser and go to the address shown in the command window (usually `http://localhost:5000`). You will see the Hangfire dashboard. Log in with the admin credentials you created during setup. From the dashboard you can:

- View all scheduled, running, and completed jobs.
- Create new recurring jobs by selecting a task and setting a schedule.
- Check job history and error logs.
- Manage queues and prioritize work.

The application runs in the background, so you can close the browser and your jobs will continue to run on schedule.

## ❓ Troubleshooting

**The application does not start** – Make sure the .NET 10 runtime is installed. You can download it for free from the Microsoft website.

**The dashboard does not load** – Check that SQL Server is running and that the connection details in the configuration file are correct. Also verify that no other program is using the same port (5000 by default).

**Jobs are not running** – Confirm that the application is still running in the command window. If you closed the window, restart the application. Also check the dashboard for error messages.

**I forgot my dashboard password** – Stop the application, delete the `users.db` file in the application folder, and restart. You will be prompted to create a new admin account.

**Download link does not work** – Visit the releases page again and choose the latest version. If the problem continues, try a different web browser.

Keywords: aspnet-core, background-jobs, background-services, csharp, dotnet, dotnet10, entity-framework-core, hangfire, job-scheduler, recurring-jobs, sql-server, swagger, web-api