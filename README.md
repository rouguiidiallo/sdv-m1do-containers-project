# Sup de Vinci - Containers module project

*Tested with `rust v1.82.0` et `node 23.0.0`.*

## Development

### API

#### Basics

Use `cargo run` to start the dev environment.

You can also install [cargo-watch](https://crates.io/crates/cargo-watch) to watche over your project's source for changes, and runs Cargo commands when they occur : `cargo-watch -x run`.

#### Using Docker

> TODO

### Web

#### Basics

Use `npm install` to install all dependancies, and `npm run dev` to start the dev environment.

#### Using Docker

> TODO

## Production

### API

#### Basics

Run `cargo build --release` to build and compile the app. This will create an executable in `/target/release/sdv-api`.

#### Using Docker

> TODO

### Web

#### Basics

Run `npm run build` to build the application, and run `npm run start` to start the Node.js server. 

#### Using Docker

> TODO
>
> WEB:
  --Dockerfile: construit l'image du front
> API
  --Dockerfile: qui permet de construire l'image du back
> Docker compose: docker-compose up permettant de construire et de lancer les conteneurs
>
> ci.yml se trouvant dans .github/workflows permettant de lancer un pipeline 


-- Soucis rencontré:
  -connexion à github pour pousser des commit
  -debogage web, pipeline
  -
