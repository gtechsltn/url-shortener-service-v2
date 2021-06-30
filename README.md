# url-shortener-service
POC API service that serves to shorten URLs

Project arhitecture:
![Project Arhitecture](https://user-images.githubusercontent.com/28594128/123982511-63bb4700-d9c3-11eb-9131-13c4ade16055.png)

API endpoints:

| HTTP method   | POST            |
| :---          | :---            | 
| URI           | /shorten        |
| Request Body  | Example:{ url: “http://stackoverflow.com/questions/1567929/website-safe-data- accessarchitecture-question?rq=1“ }|
| Reponse Type  | application/json|
| Response  | Example: { shortUrl: “http://yourservice.com/xYzw3b“ }|

| HTTP method   | GET           |
| :---          | :---            | 
| URI           | /{hash}      |
| Reponse Type  | application/json|
| Response  | Example:{ url: “http://stackoverflow.com/questions/1567929/website-safe-data- accessarchitecture-question?rq=1“ }|


Swagger Test UI:
![swaggerTestUI](https://user-images.githubusercontent.com/28594128/123982561-6c138200-d9c3-11eb-8231-648619582f44.png)
