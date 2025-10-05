---

# 🏥 Clinica Express – Backend API

In this project I’m building a **clinic backend system** using **Express.js**.
It’s a simple CRUD application for managing **technicians**, each having an **ID**, **CRM (unique)**, **name**, and **specialty**.

---

## 🛠 Tech Stack

* **Node.js** – Runtime environment
* **Express.js** – Web framework
* **PostgreSQL** – Database
* **Prisma** - ORM
* **Zod** - Validations
* **Swagger** - Documentation

---

## 📦 Installation

Clone this repository:

```bash
git clone https://github.com/MatCalixto/clinica-express.git
```

Go into the project folder:

```bash
cd clinica-express
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

---

## ▶️ Usage

Once running, the server will be available at:

```
http://localhost:3333
```

The swagger api will be available at:

```
http://localhost:3333/api-docs
```

### API Endpoint (Technicians 👨‍⚕️👩‍⚕️)

| Method | Endpoint               | Description                |
| ------ | ---------------------- | -------------------------- |
| GET    | `/api/medicos`         | Get all technicians        |
| GET    | `/api/medicos/:id`     | Get a technician by CRM/ID |
| POST   | `/api/medicos`         | Add a new technician       |
| PUT    | `/api/medicos/:id`     | Update a technician’s data |
| DELETE | `/api/medicos/:id`     | Remove a technician        |

### API Endpoint (Pacients 🤒)

| Method | Endpoint               | Description                |
| ------ | ---------------------- | -------------------------- |
| GET    | `/api/pacientes`       | Get all pacients           |
| GET    | `/api/pacientes/:id`   | Get a pacient by CRM/ID    |
| POST   | `/api/pacientes`       | Add a new pacient          |
| PUT    | `/api/pacientes/:id`   | Update a pacient’s data    |
| DELETE | `/api/pacientes/:id`   | Remove a pacient           |


### API Endpoint (Secretary 👩🏻‍💻)

| Method | Endpoint               | Description                |
| ------ | ---------------------- | -------------------------- |
| GET    | `/api/secretarios`     | Get all secretaries        |
| GET    | `/api/secretarios/:id` | Get a secretary by CRM/ID  |
| POST   | `/api/secretarios`     | Add a new secretary        |
| PUT    | `/api/secretarios/:id` | Update a secretary’s data  |
| DELETE | `/api/secretarios/:id` | Remove a secretary         |

### API Endpoint (Medical Appointment 📝🩺)

| Method | Endpoint               | Description                |
| ------ | ---------------------- | -------------------------- |
| GET    | `/api/consultas`       | Get all appointments       |
| GET    | `/api/consultas/:id`   | Get a appointment by CRM/ID|
| POST   | `/api/consultas`       | Add a new appointment      |
| PUT    | `/api/consultas/:id`   | Update a appointment’s data|
| DELETE | `/api/consultas/:id`   | Remove a appointment       |

---
