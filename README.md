# Rails React Starter

## Getting Started

### Rails side

Add docker rails alias (must be done on every new terminal)

```bash 
alias docked='docker run --rm -it -v ${PWD}:/rails -v ruby-bundle-cache:/bundle -p 3000:3000 ghcr.io/rails/cli'
```

Install bundler dependencies

```bash
docked bundle install
```

Create database

```bash
docked rails db:reset
```

Start rails server

```bash
docked rails s
```

### React side

Install dependencies

```bash
npm install
```

Start react server

```bash
npm run dev
```
