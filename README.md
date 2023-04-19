# Template

This template is setup with the followings:
- Frontend: ViteJS + ReactJS + Typescript
- Backend: Poetry + Python 3.11 + FastAPI + uvicorn

## Development

### App

0. Go do the `app` directory
```
cd app
```

1. Install the dependencies
```
npm install
```

2. Run the development server
```
npm run dev
```

### API

0. Go do the `api` directory
```
cd api
```

1. Install the dependencies
```
poetry install
```

2. Run the development server
```
uvicorn api.server:app --reload
```
