# wordpress
Deploy Wordpress to Now in one command

Firstly, make a `.env` file and copy and paste

```
{
  "env": [
    "DB_HOST",
    "DB_NAME",
    "DB_USER",
    "DB_PASSWORD",
    "SENDGRID_API_KEY",
    "SENDGRID_FROM_NAME",
    "SENDGRID_FROM_EMAIL"
  ]
}
```

Then run `now` from the project root and you will be prompted to enter these environment variables
