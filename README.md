# Aura OS

This repository hosts the Aura OS application.

## Importing the Base44 builder app

The Aura OS app is built in the Base44 builder. To get its generated source code
into this repository, connect the repo from inside the builder's GitHub
integration (app settings → Connect to GitHub / repository sync). The builder
will push the app's generated frontend and backend source into this repo.

Once the code is here, run the app locally with:

```bash
docker compose -f docker-compose.base44.yml up -d --build
```

The app is served on http://localhost:3000.
