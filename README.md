# Hugo Directus Blog

## Description
Blog app using Hugo for the frontend and Directus for the backend.

## Set Up Directus

- Make sure Docker is installed.

```bash
cd directus
docker compose up
```

## Set Up Hugo

- Make sure Hugo is installed.

In a new terminal session:

```bash
cd my-website
hugo -s prebuild && hugo serve
```

## Test Project

Visit `http://localhost:1315` in your browser to see your Hugo site.
