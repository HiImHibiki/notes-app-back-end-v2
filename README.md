<h1 align="center">Notes App Backend</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-2.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

## About The Project

A basic note-taking backend api with authentication and collaboration system added


### Built With

- [Hapi](https://hapi.dev/)
- [PostgreSQL](https://www.postgresql.org/)
- [pg-migrate](https://github.com/salsita/node-pg-migrate)
- [Redis](https://redis.io/)
- [RabbitMQ](https://www.rabbitmq.com/)


## Install

1. Clone the repo
   ```sh
   git clone https://github.com/HiImHibiki/notes-app-back-end-v2.git
   ```
2. `cd` into repo and install NPM packages
   ```sh
   cd notes-app-back-end-v2
   npm install
   ```
3. Copy `.env.example` to `.env` and fill in your credentials

4. Create the database using `pg-migate`
   ```sh
   npm run migrate up
   ```

## Usage

- Production
  ```sh
  npm run start-prod
  ```
- Development
  ```sh
  npm run start-dev
  ```


## Author

👤 **Mario Rufisanto**

- Website: https://github.com/HiImHibiki
- Github: [@HiImHibiki](https://github.com/HiImHibiki)
- LinkedIn: [@Mario Rufisanto](https://www.linkedin.com/in/mario-rufisanto-a8817a202/)

## Show your support

Give a ⭐️ if this project helped you!
