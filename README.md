# Swagger-API_Restaurant_Example
Here we use Swagger with a restaurant application, using POST and DELETE

![SWR](https://drive.google.com/uc?export=view&id=1sNDjjrrmqFTqBgJO10SvxpFuBFE2HoKi)
In **swagger.json** we insert the code to delete items:
```json:
"/restaurant/{id}": {
            "parameters": [
                {
                    "name": "id",
                    "in": "path",
                    "required": true,
                    "description": "ID of restaurant that we want to delete",
                    "type": "integer"
                }
            ],
            "delete": {}
        }
    }
