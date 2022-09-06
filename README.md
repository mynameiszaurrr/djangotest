What can this project:
- this project have a model for storing mortgage offers;
- this project have ViewSet to implement the CRUD functionality of mortgage offers.
- this project have filter mortgage offers, according to the entered parameters.

CRUD functionality is available via API:
- POST and GET - http://localhost:8000/api/offer/
- PATCH http://localhost:8000/api/offer/102/
- DELETE http://localhost:8000/api/offer/id/ where id is the id number in the database of the specific mortgage offer

The functionality is implemented using Django, DRF, django-filters.
HTML/css is implemented using BS5
