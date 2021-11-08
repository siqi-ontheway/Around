# Around
- Project web link:
https://prod.dnn2mcydupupt.amplifyapp.com
(Demo Link Deprecated)
- Launched a scalable web service in Go to handle posts and deployed to Google Cloud (Google Kubernetes Engine) 
- Used ElasticSearch (deployed to GCE) to provide geo-location based search functions such that users can search nearby posts within a distance (e.g. 200km)
- Used Google Vision API to provide a face detection model and integrate with the Go service.
## Elasticsearch
I use Elasticsearch as a NoSQL database to store data posted by users. In addition, I create a geo index for the geolocation of each post so that I can provide a quick geolocation-based search for my users.

