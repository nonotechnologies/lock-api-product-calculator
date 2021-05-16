# lock-api-product-calculator

this is a ndoe express project integrate with firebase
npm start to run
firebase deploy to deploy
docker build -t node-api .       
docker tag node-api asia.gcr.io/node-cloud-run-313900/node-api
docker push asia.gcr.io/node-cloud-run-313900/node-api
gcloud builds submit --tag asia.gcr.io/node-cloud-run-313900/node-api
gcloud run deploy --image asia.gcr.io/node-cloud-run-313900/node-api --platform managed

