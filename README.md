- Installer PostgreSQL sur le nouvel ordinateur.
- Créer une nouvelle base de données. "Biblios"
- Configurer .env.local avec les bons identifiants PostgreSQL.
- Lancer symfony bin/console doctrine:migrations:migrate pour recréer les tables et relations.

DATABASE_URL="postgresql://<nom>:<password>@127.0.0.1:5432/<nomBDD>?serverVersion=18&charset=utf8"
