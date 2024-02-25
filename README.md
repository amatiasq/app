# Template for web apps

## How to run

Note: feel free to use `bun` instead of `npm`.

1. Clone and install dependencies
```sh
NAME='my-cool-app'
git clone git@github.com:amatiasq/app "$NAME"
cd "$NAME"
npm install
```

2. Run supabase
```sh
npm run supabase
```

3. Run vite
```sh
npm run vite
```

4. Open `http://localhost:8000`. This is supabase admin.
5. Create a user at `http://localhost:8000/project/default/auth/users`
5. Open whatever port Vite used (`http://localhost:5173` maybe)
6. Login with that user

## How to deploy

Push to a Github repo of yours
This will output a docker-compose.yml for you to run.
[not true]
