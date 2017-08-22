# GetBearerToken

Azure REST Api で利用する Bearer Token を取得する LogicFlow<br />
Obtain Bearer Token to be used with Azure REST Api, with LogicApps！

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fahf0124%2FGetBearerToken%2Fmaster%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

![LogicFlow](https://github.com/ahf0124/LogicFlow-ja/blob/master/GetBearerToken/GetBearerLogicFlow.png)

POST で呼び出す際の JSON Schema.<br />
JSON schema for calling with POST.

{<br />
  "properties": {<br />
    "client_id": {<br />
      "type": "string"<br />
    },<br />
    "client_secret": {<br />
      "type": "string"<br />
    },<br />
    "resourceurl": {<br />
      "type": "string"<br />
    },<br />
    "tenanntid": {<br />
      "type": "string"<br />
    }<br />
  },<br />
  "type": "object"<br />
}<br />
