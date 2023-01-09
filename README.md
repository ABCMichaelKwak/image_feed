gcloud builds submit --tag gcr.io/circular-symbol-324110/testrun4 --project=circular-symbol-324110

gcloud run deploy --image gcr.io/circular-symbol-324110/testrun4 --platform managed --project=circular-symbol-324110 --allow-unauthenticated