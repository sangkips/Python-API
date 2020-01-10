# Python-API
Python API Tutorial

An API (Application Programming Interface) is a set of rules that are shared by a particular service. These rules determine in which format and with which command set your application can access the service, as well as what data this service can return in the response. it acts as layer between your application and external service.
REST API (Representational state transfer) is an API that uses HTTPS requests for communication with web services.
From the python site, the REST API can be viewed as data source located on an internet address that can be accessed in a certain way through certain libraries.

Types of Requests:

a) GET: retrieve information like a search result
b) POST: adds new data to the server
c) PUT: changes existing information
d) DELETE: deletes existing information

Example of implementing GET request

>>> import requests

>>> response = requests.get('https://google.com') 

>>> print(response)

<Response [200]>

200 is a response code which can inform us on the state of the system state.

Status Codes

a) 200-OK. The request was successful.
b) 204-No content. The server successfully processed the request and did not return any content.
c) 301-Moved permanently. The server responds that the requested page(endpoint) has been moved to another address and redirects to this address.
d) 400-Bad request. The server cannot process the request because the client-side-errors(incorect request format).
e) 401-Unauthorized. Occurs when authentication failed due to incorrect credentials or even their absence.
d) 403-Forbiden. Access to the specified resource is denied.
e) 404-Not found. The requested resource was not found on the server.
f) 500-Internal Server Error. Occurs when an unknown error has occurred on the server.





