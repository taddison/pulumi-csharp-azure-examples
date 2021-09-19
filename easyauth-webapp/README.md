## Getting Started

Update the values in `Pulumi.dev.yaml`.  You can use `az account list` for details on subscriptions/tenant/userId.  I would suggest using the same name for both the site, and the app registration.

After that deploy:

```shell
pulumi up
```

## Notes

Deployment of the web app is fine, but the app-registration/app auth isn't 100% working (you will have to go clickops in the Azure portal).