# Platform Releases 

LDS Connector

| Platform release  | Metadata model    | LDS - EDC        | LDS - Proxy  | LDS Connector UI      | LDS - Proxy ElasticSearch  | LDS - EDC - Connector Postgresql    |  In Connector IAM | Installation  scripts        |  Active deployment     |
| ----------------- | ----------------- | ---------------- |------------- | ------------- | -------------------------- | ------------------------- |  ---------------- | ---------------------------- | ---------------------- | 
| 1.0.0-beta <br>        | [0.8.0](https://github.com/LanguageDataSpace/lds-model/releases/tag/v0.8.0) | [0.8.0](https://github.com/LanguageDataSpace/lds-edc/tree/edc0.8.0) <br> Docker Images: languagedataspace/dataplane:edc0.8.0dapsiam languagedataspace/controlplane:edc0.8.0dapsiam | [0.8.0](https://github.com/LanguageDataSpace/lds-proxy-backend/tree/0.8.0) <br> Docker Image: languagedataspace/edcproxy:0.8.0 <br> | [main](https://github.com/LanguageDataSpace/lds-edc-ui/tree/main) <br> Docker Image: languagedataspace/lds-ui:main | 8.10.2 <br> Docker Image: elasticsearch:8.10.2 <br>| 15.0.0 <br> Docker Image: bitnami/postgresql:15.0.0 |  Docker Image: languagedataspace/lds-iam:60110 | [0.8.0prod](https://github.com/LanguageDataSpace/Deployment/tree/0.8.0prod) | http://ldssetup.ilsp.gr:9876/, http://ldssetup.ilsp.gr:9877/, http://ldssetup.ilsp.gr:9878/|
| 0.5 <br>        | [0.8.0](https://github.com/LanguageDataSpace/lds-model/releases/tag/v0.8.0) | [0.7.0](https://github.com/LanguageDataSpace/lds-edc/tree/edc0.7.0) <br> Docker Images: languagedataspace/dataplane:edc0.7.0 languagedataspace/controlplane:edc0.7.0 | [0.7.0](https://github.com/LanguageDataSpace/lds-proxy-backend/tree/0.7.0) <br> Docker Image: languagedataspace/edcproxy:0.7.0 <br> | [0.7.0](https://github.com/LanguageDataSpace/lds-edc-ui/tree/0.7.0) <br> Docker Image: languagedataspace/lds-ui:0.7.0 | 8.10.2 <br> Docker Image: elasticsearch:8.10.2 <br>| 15.0.0 <br> Docker Image: bitnami/postgresql:15.0.0  | No | [0.7.0](https://github.com/LanguageDataSpace/Deployment/tree/0.7.0) | N/A |
| 0.1-alpha <br>        | 0.5.0 | [0.3.1](https://github.com/LanguageDataSpace/lds-edc/tree/edc0.3.1) <br> Docker Images: languagedataspace/dataplane:edc0.3.1 languagedataspace/controlplane:edc0.3.1 | [0.3.1](https://github.com/LanguageDataSpace/lds-proxy-backend/tree/0.3.1) <br> Docker Image: languagedataspace/edcproxy:0.3.1 <br> | [0.3.1patch](https://github.com/LanguageDataSpace/lds-edc-ui/tree/0.3.1patch) <br> Docker Image: languagedataspace/lds-ui:0.3.1patch | 8.10.2 <br> Docker Image: elasticsearch:8.10.2 <br>| 15.0.0 <br> Docker Image: bitnami/postgresql:15.0.0 | No | [0.3.1](https://github.com/LanguageDataSpace/Deployment/tree/0.3.1) | N/A |

LDS Participant Registry

| Platform release     |       DAPS                                     |  Registry backend        | Registry UI  |   Installation  scripts                                                  |      Active deployment             |
| -------------------- | ---------------------------------------------- | ------------------------ |------------- |  ----------------------------------------------------------------------  | ---------------------------------- |
| 1.0.0-beta <br> |   Docker Image: languagedataspace/kc-daps:main |                          |              |   https://github.com/LanguageDataSpace/DeploymentCentral/tree/0.8.0prod  |  http://ldssetup.ilsp.gr:2873/    | 







