# Node.js CRUD app with JWT auth & MySQL

This repository contains a simple CRUD application built using Node.js, Express.js, EJS, JWT, and Sequelize with MySQL as the database dialect. The application allows users to create, read, update, and delete records in a MySQL database, with JWT authentication protecting certain routes to ensure secure access to data.

## Table of Contents

- [Installation⚙️](#installation)
- [Usage💻](#usage)
- [Testing🛠️](#testing)
- [Contributing🧑🏽‍💻](#contributing)
- [License📜](#license)

## Installation

Clone this repository to your local machine:

```
git clone https://github.com/killy10o10/node-express-sequelize.git
```

Navigate to the project directory:

```
cd node-express-sequelize
```

Install the project dependencies:

```
npm install
```

Create a new MySQL database and update the database configuration file at `config/database.js` with your MySQL credentials.

Run the database migrations:

```
npx sequelize-cli db:migrate
```

Start the server:

```
npm run start
```

Access the app in your web browser at `http://localhost:3000`.

## Usage

### Personal To-Do List

As an individual user, you can use this API to manage your personal to-do list. You can create a new to-do list and add tasks to it using the API. Once you have completed a task, you can mark it as done or delete it from your list.

### Team Project Management

If you are working on a project with a team, you can use this API to manage your tasks and deadlines. You can create a to-do list for each project and assign tasks to team members. Team members can view their tasks and update their progress, which can help you stay on track and ensure that everyone is on the same page.

### Education

Teachers can use this API to create to-do lists for their students. They can assign homework and deadlines to their students and track their progress. This can help teachers keep track of their students' progress and ensure that they are meeting their learning goals.

### Fitness Tracking

You can use this API to create a fitness to-do list. You can set goals for your workouts and track your progress. This can help you stay motivated and ensure that you are making progress towards your fitness goals.

### Grocery List

You can use this API to create a grocery list. You can add items to the list and mark them as purchased once they are bought. This can help you stay organized and ensure that you don't forget anything when you go grocery shopping.

## Testing

You can test the API using tools like Postman or cURL. To test the API endpoints, you will need to have an access token, which you can obtain by authenticating with your username and password. Once you have the access token, you can include it in your requests to access the protected routes.

## Contributing

Contributions are always welcome! If you find any bugs or have any suggestions for improvement, please open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).