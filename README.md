## Getting Started
This repository includes files with plain SQL that can be used to recreate a database:

- Use [schema.sql](./schema.sql) to create all tables.
- Use [data.sql](./data.sql) to populate tables with sample data.
- Check [queries.sql](./queries.sql) for examples of queries that can be run on a newly created database. 

**Important note: this file might include queries that make changes in the database (e.g., remove records). Use them responsibly!**

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
    - [Run tests](#run-tests)
    - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Clinic Database <a name="about-project"></a>

The **Clinic Database** is a simple database that stores information about the animals in the vet.

## 🛠 Built With <a name="built-with"></a>
<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://reactjs.org/">React.js</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

> The three key features of this project include the following.

- **Query and update the paitents table.**
- **Record of all patients**
- **Query multiple tables.**
- **Add "join table" for vists.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>
Get ready to explore Clinic Database with these steps:

**Schema Diagram**


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need: PostgreSQL

### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone git@github.com:ticoniq/clinic.git
```

### Install

Install this project with: Install [PostgreSQL](https://www.postgresql.org/download/)

### Usage

To run the project, execute the following command:
- Start the PostgreSQL server
- Run psql
- Create the database with: `CREATE DATABASE clinic;`
- Connect to the database with: `\c clinic`
- Create the tables with the queries from [schema_based_on_diagram.sql](./schema_based_on_diagram.sql)

### Run tests

To run tests, run the following command: **Not available**

### Deployment

You can deploy this project using: **Not available**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Mohamed Aden Ighe**

- GitHub: [@katarighe](https://github.com/katarighe)
- Twitter: [@katarighe](https://twitter.com/katarighe)
- LinkedIn: [@mighe](https://linkedin.com/in/mighe)

👤 **Noel Nomgne Foka**

- GitHub: [@noelnomgne](https://github.com/noelfoka)
- Twitter: [@noelnomgne](https://twitter.com/noelnomgne)
- LinkedIn: [@noelnomgne](https://www.linkedin.com/in/noelfoka/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

> Here are some future features that could be added to the Clinic Database in the future.

- **User authentication and authorization:** This would allow users to create accounts, sign in and out, and have their own personal items.

These are just a few ideas for future features that could be added to the Clinic Database. The specific features that are added will depend on the needs and wants of the users.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

Give a star⭐️ or a thumbs up 👍 if you like this project! You can visit my GitHub profile for more of my projects.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Project supervised by [Microverse](https://www.microverse.org/)
- [Creative Commons 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
