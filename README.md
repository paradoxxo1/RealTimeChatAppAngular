```markdown
# Real-Time Chat Application

This is a real-time chat application built with .NET 8.0, Angular 18, and SignalR. The application allows users to join chat rooms and send messages in real-time.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time messaging using SignalR
- Multiple chat rooms support
- User-friendly interface with Angular
- Scalable and maintainable architecture with .NET 8.0

## Prerequisites
- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Node.js and npm](https://nodejs.org/) (for Angular)
- [Angular CLI](https://angular.io/cli) (install globally using `npm install -g @angular/cli`)

## Installation

### Backend (.NET 8.0)
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chat-application.git
    cd chat-application/backend
    ```
2. Restore the .NET packages:
    ```bash
    dotnet restore
    ```

### Frontend (Angular 18)
1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```
2. Install Angular dependencies:
    ```bash
    npm install
    ```

## Running the Application

### Backend
1. Navigate to the backend directory:
    ```bash
    cd backend
    ```
2. Run the application:
    ```bash
    dotnet run
    ```
   The backend server will start on `https://localhost:5001`.

### Frontend
1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```
2. Start the Angular development server:
    ```bash
    ng serve
    ```
   The frontend application will start on `http://localhost:4200`.

## Project Structure
```
chat-application/
├── backend/
│   ├── Controllers/
│   ├── Hubs/
│   ├── Models/
│   ├── Services/
│   ├── Program.cs
│   └── Startup.cs
└── frontend/
    ├── src/
    │   ├── app/
    │   ├── assets/
    │   ├── environments/
    │   ├── index.html
    │   ├── main.ts
    │   └── styles.css
    ├── angular.json
    ├── package.json
    └── tsconfig.json
```

![1](https://github.com/paradoxxo1/RealTimeChatAppAngular/assets/124463263/6314e875-d8d7-45d9-be3d-e0534bf03f4f)
![2](https://github.com/paradoxxo1/RealTimeChatAppAngular/assets/124463263/69b9d6d4-463c-4307-93fd-1301ec5ea83d)
![3](https://github.com/paradoxxo1/RealTimeChatAppAngular/assets/124463263/0320390a-f41a-411b-9e13-320cb07101ca)
![4](https://github.com/paradoxxo1/RealTimeChatAppAngular/assets/124463263/561d2ea9-423b-4e67-a201-e635f54ff728)



## Usage
1. Open your browser and navigate to `http://localhost:4200`.
2. Enter a username to join a chat room.
3. Start sending messages in real-time!

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
