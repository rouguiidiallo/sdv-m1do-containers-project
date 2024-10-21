# Utiliser l'image officielle Rust avec la version 1.82
FROM rust:1.82

# Créer un répertoire de travail
WORKDIR /app

# Copier le fichier Cargo.toml et Cargo.lock pour construire le cache des dépendances
COPY Cargo.toml Cargo.lock ./

# Créer le répertoire target
RUN mkdir src

# Copier le code source
COPY src ./src

# Compiler l'application
RUN cargo build --release

# Spécifier la commande à exécuter lors du démarrage du conteneur
CMD ["cargo", "run"]




