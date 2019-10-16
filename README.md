DATABASE / LAYOUT / ROUTES

- SERVER -> routes/index.js

      const express = require('express')
      const router = express.Router()
      router.get('/', (req, res) => { res.render('index') })
      module.exports = router

- views/layouts -> estrutura base html

      <body>
        <%- include('../partials/header.ejs') %>
        <%- include('../partials/errorMessage.ejs') %>
        <%- body %>
      </body>

- routes/authors.js ->











<!-- DATABASE_URL=mongodb+srv://esterdev:esterdev@omnistack-cjkv9.mongodb.net/mylibrary?retryWrites=true&w=majority -->