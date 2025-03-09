# LINKEDIN-BOT

This is a LinkedIn automation bot that automatically accepts all connection invitations. This project is a cloned repository that I have worked on and modified.

## Running it Locally on Your Machine

1) Clone this repository and navigate to the project root.
2) Create a `.env` file and add your LinkedIn username and password.
3) Ensure that Node.js is installed on your system.
4) Install ChromeDriver on your system.
5) Install dependencies using:
```sh
npm install
```
6) Run the bot using:
```sh
node index.js
```

## Running it on a Cloud Instance (e.g., AWS)

1) SSH into your cloud instance.
2) Clone this repository.
3) Configure your environment variables:
   - **MacOS/Linux**
     ```sh
     export USERNAME="your_linkedin_username"
     export PASSWORD="your_linkedin_password"
     ```
   - **Windows-CMD**
     ```sh
     setx USERNAME "your_linkedin_username"
     setx PASSWORD "your_linkedin_password"
     ```
   - **PowerShell**
     ```sh
     $Env:USERNAME="your_linkedin_username"
     $Env:PASSWORD="your_linkedin_password"
     ```
4) Install Node.js and ChromeDriver.
5) Navigate to the project root and install dependencies:
```sh
npm install
```
6) Run the application:
   - Start the script manually:
     ```sh
     node index.js
     ```
   - Run using PM2 for better process management:
     ```sh
     npm install pm2@latest -g && pm2 start index.js
     ```


