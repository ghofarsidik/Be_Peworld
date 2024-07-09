<div align="center">
  <a href="https://github.com/ghofarsidik/Be_Peworld.git">
      <img src="https://github.com/ghofarsidik/Peworld/blob/65f3d7f14e2bc24f66753f9b14f50830ce7c0f2c/src/components/images/logo/logo.png" width="350"/>
  </a>

  <h1 align="center">Peworld</h1>

  <p align="center">
     Peworld Implementation
    <br />
    <br />
    <a href="https://peword-ags.netlify.app/" target="_blank">View Website Demo</a>
    ·
     <a href="https://github.com/ghofarsidik/Peworld" target="_blank">View Front-End Repo</a>
  </p>
</div>

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project-)
  - [Built With](#built-with)
- [Getting Started](#-getting-started)
  - [Prerequisites](#-prerequisites)
  - [Installation](#-installation)
  - [Usage](#-usage)
- [Directory Structure](#-directory-structure)
- [Documentation](#-documentation)
- [Contributing](#contributing-)
- [Contact](#️-contact)
- [Project Relate](#-project-related)




## About The Project 🖥️

The back-end for **Peworld** was crafted by [muhammadrisano](https://github.com/muhammadrisano). The source code is available for exploration, as I have forked it from the original repository. It contains all the necessary files and documentation to develop and operate the server side of this application. Many thanks to [muhammadrisano](https://github.com/muhammadrisano) for their contribution to this back-end project.

### Built With

- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/en)
- [MongoDB](https://www.mongodb.com/)


## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### 🔄 Prerequisites

Ensure you have the following installed on your local machine:

- Node.js
- npm

### 🚀 Installation

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/ghofarsidik/Be_Peworld.git
   ```

2. **Navigate to the workspace**:
   ```sh
      cd Be_Peworld
   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Start Development Server**:
   ```bash
   nodemon
   ```
   If that doesn't work, try:
   ```bash
   node index.js
   ```

    Open the project in your preferred code editor

    ```sh
      code .
    ```


The server will start on port 3000 by default. You can use Postman to interact with the endpoints in [Documentation](#-documentation).

## 💻 Usage

To use this project, follow the instructions below to understand the project structure and how to use the provided API documentation.

### 📂 Directory Structure

```
Be_Peworld/
├── node_modules/
├── public/
│   └── peworld.png
├── src/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── auth/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── experience/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── hire/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── portfolio/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── recruiter/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── skill/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── workers/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   └── upload.js
│   ├── helpers/
│   │   ├── auth.js
│   │   └── common.js
│   ├── middlewares/
│   │   ├── auth.js
│   │   └── upload.js
│   ├── models/
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── users.js
│   │   └── workers.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── index.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── upload.js
│   │   └── workers.js
│   └── utils/
│       └── cloudinary.js
├── .gitignore
├── README.md
├── index.js
├── package-lock.json
├── package.json
├── vercel.json
└── yarn.lock
```

### 📚 Documentation

Explore the comprehensive API documentation for the **Peworld** project, crafted by [Muhammad Risano](https://github.com/muhammadrisano). This documentation is designed to facilitate the testing of endpoints and provide insight into the structure and functionality of the project's APIs.

[![Peworld API Postman Documentation](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/34293182/2sA3e2f9TH)

## Contributing 🤝

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Here's how you can contribute to the project:

1. **Fork the Project**: Click the 'Fork' button on the top right of the repository.
2. **Create your Feature Branch**: Go to your forked repository, and click on the 'Branch' button. Create a new branch with a descriptive name (e.g. `git checkout -b feature/AmazingFeature`).
3. **Commit your Changes**: After making your changes, click on the 'Commit' button. Write a short, descriptive commit message.
4. **Push to the Branch**: Once you've committed your changes, click on the 'Push' button to push your changes to your forked repository.
5. **Open a Pull Request**: Go to the 'Pull Requests' tab in the original repository. Click on the 'New Pull Request' button. Select your forked repository and the branch you just pushed. Write a descriptive title and message for your pull request, and click on the 'Create Pull Request' button.

That's it! Your changes will be reviewed, and if everything looks good, they will be merged into the main project. Thank you for your contribution!

## ☎️ Contact
For any questions or inquiries about this project, please don't hesitate to reach out to us:

Email: ghofarassidik@gmail.com

Alternatively, for back-end related issues, you can contact [muhammadrisano](https://github.com/muhammadrisano) directly.

### 📂 Project Related

- 🚀 [`Front-End Project Repository Link`](https://github.com/ghofarsidik/Peworld.git)
- 🚀 [`Front-End Demonstration Link`](https://peword-ags.netlify.app)
- 🚀 [`Back-End Demonstration Link`]( https://fwm17-be-peword.vercel.app/v1/workers)