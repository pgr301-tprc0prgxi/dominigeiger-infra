# dominigeiger-infra

## Environment Variables for travis

For the pipeline to work you will have to add the following environment variables:

```
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
STATUSCAKE_USERNAME
STATUSCAKE_APIKEY
OPSGENIE_API_KEY
TF_VAR_logztoken
TF_VAR_logzurl
HEROKU_EMAIL
HEROKU_API_KEY
```

*Also you will have to change the variables in `variables.tf` and the heroku deploy config in the [app-repo](https://github.com/pgr301-tprc0prgxi/dominigeiger-app)*
