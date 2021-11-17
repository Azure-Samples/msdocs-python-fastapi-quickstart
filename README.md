---
page_type: sample
description: "A minimal sample app that can be used to demonstrate deploying FastAPI apps to Azure App Service on Linux."
languages:
- python
products:
- azure
- azure-app-service
---

# Python FastAPI sample for Azure App Service (Linux)

This is a minimal FastAPI app that can be deployed to Azure App Service on Linux.

### Install the requrements
`pip install -r requirements.txt`

### Start the application
`uvicorn main:app --reload`

### Example call
http://127.0.0.1:8000/items/4?q=my%20test%20query

### Example json response
`{"item_id": 4, "q": "my test query"}`


# More information
For additional instructions on running the code as well as deploying it to Azure, see [Quickstart: Create a Python app in Azure App Service on Linux](https://docs.microsoft.com/azure/app-service/quickstart-python).

To learn more about FastAPI, see [FastAPI](https://fastapi.tiangolo.com/).

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
