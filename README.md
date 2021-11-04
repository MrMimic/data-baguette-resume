# data-baguette resume

## Login gcloud

```bash
    gcloud auth login
    gcloud config set project data-baguette
```

## Build Docker

```bash
    gcloud builds submit --tag gcr.io/data-baguette/resume
```

## Run Docker

```bash
    gcloud run deploy --image gcr.io/data-baguette/resume --platform managed --max-instances=1
```
