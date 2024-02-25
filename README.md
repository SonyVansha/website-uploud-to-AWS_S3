# Uploud Objects to S3 AWS from Simple Website

## Architecture

![image](https://github.com/SonyVansha/website-uploud-to-AWS_S3/assets/152833966/0eb5423d-c726-456f-8852-4d89f4d7ff11)


## Crete File Environment (.env)
| **Environment** | **Source environment** |
|--|--|
| **REGION** | (Region) |
| **NAME_BUCKET** | - |
| **AWS_ACCESS_KEY_ID** | - |
| **AWS_SECRET_ACCESS_KEY** | - |
put
## Font-End Setup

### Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run start
```

Runs the app in the development mode.\
Open [http://localhost:8080](http://localhost:8080) to view it in your browser.


## CORS Setup S3

```sh
[
    {
        "AllowedHeaders": [
            "*"
        ],
        "AllowedMethods": [
            "GET",
            "POST",
            "PUT"
        ],
        "AllowedOrigins": [
            "*"
        ],
        "ExposeHeaders": []
    }
]
```
