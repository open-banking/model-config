For detailed specification, you can visit https://openbanking.atlassian.net/wiki/spaces/DZ/pages/1077805674/Offers+v3.1.2

To generate the project, go to https://codegen.lightapi.net and select single project from the menu. 

If you have light-codegen built locally in networknt folder. 

```
cd ~
java -jar networknt/light-codegen/codegen-cli/target/codegen-cli.jar -f openapi -o open-banking/offers/generated -m open-banking/model-config/ob/offers/openapi.yaml -c open-banking/model-config/ob/offers/config.json
```

