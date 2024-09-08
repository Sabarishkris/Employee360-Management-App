# Employee360 App

Employee360 is a role-based employee management application designed with Kotlin and Jetpack Compose.
It offers different views and functionalities based on the role of the user (Admin, Manager, or Employee).

## Features
### Login View 
![login](https://github.com/user-attachments/assets/1e35f0a3-8e0b-4985-aec8-d30a510e4513)

### 1. Admin View:
### Screenshot
![admin](https://github.com/user-attachments/assets/759d50f0-db68-41c9-83dc-bed7e516b9ad)

1. **Dashboard Screen**:
   - Displays the total number of employees, teams.
   - Lists the last 5 employees who joined new.
   -  Graph to show employee count for each team.
   
2. **Employee List Screen**:
   - Shows employee details: name, designation, team, salary, and profile image.
   - Option to add new employees and new Team.

3. **Settings Screen**:
   - Sign-out functionality.
   - About login person.

### 2. Manager View:
### Screenshot
![manager](https://github.com/user-attachments/assets/8deb5bee-6a3d-4d2f-9dd2-2e9a4845a5d2)

1. **Dashboard Screen**:
   - Displays the total number of employees in the manager's team.
   - Lists the last 5 employees who joined their team.

2. **Employee List Screen**:
   - Displays team members' details: name, designation, team, salary, and profile image.

3. **Settings Screen**:
   - Sign-out functionality.
   - About login person.

### 3. Employee View:
### Screenshot
![employee](https://github.com/user-attachments/assets/6daa50f9-5314-4dfb-94b5-02e3e79faa02)

1. **Detail Screen**:
   - Displays personal details of the logged-in employee.

2. **Settings Screen**:
   - Sign-out functionality.

## Additional Features

- **Material Design 3**: The app fully utilizes Material Design 3, providing a modern UI experience with dynamic theming and adaptive components.
- **Forgot Password**: Users can reset their passwords using the Forgot Password option available on the login screen .

## Tech Stack

- **Language**: Kotlin
- **Framework**: Jetpack Compose
- **Architecture**: MVVM
- **Database**: Room
- **Image Loading**: Coil



