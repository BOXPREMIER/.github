# BoxPremier

Plataforma de suscripción de vinos premium con gestión automatizada de pedidos y pagos.

---

## Repositorios

### [boxpremier-server](https://github.com/BOXPREMIER/boxpremier-server)
API RESTful backend construida con Node.js, Express y MongoDB.

**Stack:**
- Node.js + Express 5
- MongoDB + Mongoose
- JWT Authentication
- Jest + Supertest

**Features:**
- Sistema de suscripciones (regular y regalo)
- Gestión de pedidos
- Panel administrativo
- Exportación de datos a CSV

### [boxpremier-client](https://github.com/BOXPREMIER/boxpremier-client)
Aplicación frontend construida con React.

**Stack:**
- React + Vite
- Zustand para estado
- Axios para HTTP
- React Router

**Features:**
- Interfaz de suscripción
- Gestión de perfil de usuario
- Dashboard administrativo con métricas
- Sistema de pagos (en desarrollo)

---

## Stack Tecnológico

**Backend:**
- Node.js 18+
- Express 5
- MongoDB 6+
- JWT + Bcrypt

**Frontend:**
- React 18+
- Vite
- Zustand
- Axios

**Pagos:** (en desarrollo)
- PayPal (planificado)
- Redsys (planificado)
- Multisafepay (planificado)

---

## Arquitectura
```
BoxPremier/
├── boxpremier-server/ # API Backend
│   ├── src/    
│       ├── config/
│       ├── controllers/
│       ├── database/
│       ├── middlewares/
│       ├── models/
│       ├── routes/
│       ├── utils/
│       ├── validations/
│       ├── tests/
│   ├── .env
│   ├── .env.test
│   ├── app.js
│   └── README.md
│
└── boxpremier-client/     # Frontend App
    ├──src/
        ├── components
        ├── layout
        ├── pages
        ├── router
        ├── services
        ├── store
        ├── tests
        ├── utils
        ├── validators
    ├── .env
    └── README.md
```

---

## 🚀 Inicio Rápido

### Backend
```bash
cd boxpremier-server
npm install
cp .env.example .env
cp .env.example .env.test
npm start
```

### Frontend
```bash
cd boxpremier-client
npm install
cp .env.example .env
npm run dev
```

---

## Documentación

- [Documentación API](hhttps://documenter.getpostman.com/view/46421388/2sB3WttK9M)
- [README Backend](https://github.com/BOXPREMIER/boxpremier-server/blob/main/README.md)
- [README Frontend](https://github.com/BOXPREMIER/boxpremier-client/blob/main/README.md)

---

## Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/angiepereir">
        <img src="https://github.com/angiepereir.png" width="100px;" alt=""/>
        <br />
        <sub><b>@angiepereir</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/nicolegugu93">
        <img src="https://github.com/nicolegugu93.png" width="100px;" alt=""/>
        <br />
        <sub><b>@nicolegugu93</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ingridD2707">
        <img src="https://github.com/ingridD2707.png" width="100px;" alt=""/>
        <br />
        <sub><b>@ingridD2707</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/marianyarj">
        <img src="https://github.com/marianyarj.png" width="100px;" alt=""/>
        <br />
        <sub><b>@marianyarj</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/priscelis">
        <img src="https://github.com/priscelis.png" width="100px;" alt=""/>
        <br />
        <sub><b>@priscelis</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ambalari">
        <img src="https://github.com/ambalari.png" width="100px;" alt=""/>
        <br />
        <sub><b>@ambalari</b></sub>
      </a>
    </td>
  </tr>
</table>