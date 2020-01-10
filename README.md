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

Status codes



