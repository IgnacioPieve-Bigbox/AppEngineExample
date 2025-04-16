# FastAPI App Engine Example

A minimal FastAPI application ready for Google App Engine deployment.

## Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the development server:
```bash
uvicorn main:app --reload
```

The application will be available at `http://localhost:8000`

## Endpoints

- `/health`: Health check endpoint

## Deployment

To deploy to Google App Engine:

```bash
gcloud app deploy
``` 