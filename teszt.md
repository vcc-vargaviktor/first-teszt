List all folders and projects, whether they are active or not.

| **Request**  |                                                             |
|--------------|-------------------------------------------------------------|
| Method       | GET                                                         |
| Resource     | https://\[customer\].asp.virtual-call-center.eu/v2/projects |
| Options      | N/A                                                         |
| Body         | N/A                                                         |
| **Response** |                                                             |
| Body         | Project array, encoded in JSON                              |

### Request

*Resource parameters*

| **Name** | **Type** | **Mandatory** | **Comment**                                       |
|----------|----------|---------------|---------------------------------------------------|
| customer | string   | yes           | Your call centre’s unique identifier (subdomain). |

### Response
