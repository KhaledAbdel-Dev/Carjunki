# Carjunki
(a complete car recycling solution)

<img width="1490" alt="Screenshot-2022-12-05-at-6 22 19-PM-2" src="https://user-images.githubusercontent.com/112451869/207965461-e34d535c-b47e-4e3d-9df2-03a4ce7edc18.png">

I created a full-stack car recycling solution. After securely signing-up/logging-in, users fill out a multi-step form detailing their vehicle specs and my custom back-end algorithm will calculate a unique quote fore the user based on their input. Assuming the user chooses to accept my offer, they would then be prompted to complete the second half of the form detailing a vehicle ownership and pickup details. Finally, they are met with a confirmation page thanking them for accepting their offer and providing some next steps.

This is a more advanced full-stack application using MVC method to operate classic CRUD functionality.

This application was created using Node.js, EJS, vanilla JavaScript and CSS. Express.js was utilized as a template handler, brought to life with TailwindCSS and supported by a MongoDB database.

# Install

1. Clone repo
2. run `npm install`

---

# Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`

---

# Run

`npm start`
