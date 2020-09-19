<h1 align="center">
    Cyan Challenge :seedling:
    <br>
</h1>

<p align="center">

  <img alt="GitHub" src="https://img.shields.io/github/license/rafacdomin/cyan-challenge.svg">
</p>

<p align="center">
  <a href="#about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#author">Author</a>
</p>

<p align="center">
  <a href="https://cyan-sugarcanes.netlify.app" target="_blank"><img src="https://api.netlify.com/api/v1/badges/553c749d-5122-4b43-a8a8-c8e6a84310e5/deploy-status" alt="Run in Netlify"></a>
<a href="https://raw.githubusercontent.com/rafacdomin/cyan-challenge/master/cyan-insomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

## About

ReactJS + NodeJS project that allow users to search on map for fields, harvests, farms, sugarcane mills and register fields in map.

<p align='center'>
  <img src="https://raw.githubusercontent.com/rafacdomin/cyan-challenge/master/.github/homepage.png" alt="Homepage" width="700"/>
</p>

## Technologies

This project was developed with the following technologies:

API:

- [NodeJS](https://nodejs.org/)
- [Express](https://expressjs.com)
- [Socket.io](https://socket.io)
- [PostgreSQL](https://www.postgresql.org)
- [Sequelize](https://sequelize.org)
- [cors](https://www.npmjs.com/package/cors)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [Json Web Token](https://jwt.io)

WEB:

- [ReactJS](https://reactjs.org)
- [Typescript](https://www.typescriptlang.org/)
- [React Router](https://reactrouter.com)
- [Leaflet](https://leafletjs.com)
- [Unform](https://unform.dev)
- [Socket.io](https://socket.io)
- [Yup](https://github.com/jquense/yup)
- [React Toastify](https://fkhadra.github.io/react-toastify/introduction)
- [React Select](https://react-select.com/home)
- [Airbnb React Dates](https://airbnb.io/projects/react-dates/)
- [styled-components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)

## How To Use
You can access the site clicking this button:

<a href="https://cyan-sugarcanes.netlify.app" target="_blank"><img src="https://api.netlify.com/api/v1/badges/553c749d-5122-4b43-a8a8-c8e6a84310e5/deploy-status" alt="Run in Netlify"></a>


To clone and run this application, you'll need installed on your computer:
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/)
- [Yarn v1](https://classic.yarnpkg.com/) 
- One instance of PostgreSQL with Postgis

> Obs.: I recommend using `docker` to create and run the PostgreSQL instance.

To run the server:

```bash
# Clone the repository
$ git clone https://github.com/rafacdomin/cyan-api

# Create the instance of postgreSQL with Postgis using docker
$ docker run --name cyanPG -e POSTGRES_USER=postgres \
              -e POSTGRES_DB=cyan -e POSTGRES_PASSWORD=docker \
              -p 5432:5432 -d postgis/postgis

# Go into the repository folder
$ cd cyan-api

```

Make a copy of .env.example to .env and set YOUR enviroment variables

```bash
# Install dependencies
$ yarn

# Run the server
$ yarn dev:server
```

To run the App Web:

```bash
# Clone the repository
$ git clone https://github.com/rafacdomin/cyan-web

# Go into the repository folder
$ cd cyan-web

# Install dependencies
$ yarn

# Run the app
$ yarn start
```

## License

This project is under the MIT license. See the [LICENSE](https://github.com/rafacdomin/cyan-challenge/blob/master/LICENSE) for more information.

---

## Author

<img  border-radius="50px" src="https://avatars3.githubusercontent.com/u/40310160?s=460&u=d2babe9b7f1c365955699550074910a1957525c8&v=4" width="100px" alt="Author"/>

Made with :purple_heart: by Rafael Domingues :wave: [Get in touch!](https://www.linkedin.com/in/rafaelcodomingues/)

[![Linkedin Badge](https://img.shields.io/badge/-Rafael_Domingues-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaelcodomingues/)](https://www.linkedin.com/in/rafaelcodomingues/)
[![Gmail Badge](https://img.shields.io/badge/-rafaelcodomingues@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rafaelcodomingues@gmail.com)](mailto:rafaelcodomingues@gmail.com)
[![DEV.to Badge](https://img.shields.io/badge/DEV.to-rafacdomin-black)](https://dev.to/rafacdomin)
[![GitHub followers](https://img.shields.io/github/followers/rafacdomin?label=Follow&style=social)](https://github.com/rafacdomin/?tab=follow)
