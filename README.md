# googlePlaceAutocomplete





## How to do this 

Make sure you are logged into your google cloude CLI [(https://cloud.google.com/sdk/gcloud/reference/auth/login)]
Clone this repository to your local
Make sure you have Node insatlled 
Open terminal from your project directory 

Run:

```
npm insall
```


```
gcloud functions deploy getPlaceFromId --runtime=nodejs16 --trigger-http --set-env-vars API_KEY=YOUR_API_KEY
```
Add your api key here so that it will be saved in environment variable(Safe)
