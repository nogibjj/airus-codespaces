![Actions](https://github.com/github/docs/actions/workflows/blank.yml/badge.svg)
![Figure](https://github.com/nogibjj/airus-codespaces/blob/main/test.png)

Set Up Auth
-----------
place in Codespace secrets
  
    DATABRICKS_HOST
    DATABRICKS_TOKEN

Test Out Cli
------------
    databricks clusters list --output JSON | jq
    databricks fs ls dbfs:/
    databricks jobs list --output JSON | jq
    
    DATABRICKS_TOKEN

