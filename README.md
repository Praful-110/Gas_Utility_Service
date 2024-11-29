# gas_utility_service
Gas utility service using Django
Features
1. Submit Service Requests: Users can submit service requests online, providing details such as the type of request and any relevant attachments.
2. Customer Management: The system allows for the management of customer information, enabling efficient handling of service requests.

CODEBASE>>>>>

Gas Utility Service

|-customer_service/
|--	gas_utility/
|	        |--	__init__.py
|	        |--	asgi.py
|	        |--	settings.py
|	        |--	urls.py
|	        |--	wsgi.py
|--	media/
|	    |--	attachments/
|			|--	My_Resume.pdf
|--	utility_services/
|	    |--	migrations/
|	    |--	templates/
|	    |	    |-- requests_submitted.html
|	    |	    |-- submit_request.html
|	    |	    |-- track_request.html
|	    |-- __init__.py
|	    |-- admin.py
|	    |-- apps.py
|	    |-- forms.py
|	    |-- models.py
|	    |-- tests.py
|	    |-- urls.py
|	    |-- views.py
|--	db.sqlite3
|--	manage.py
|
|-gas_utility/
|	|- accounts/
|	|	    |--	migrations/
|	|	    |--	templates/
|	|	    	|--	accounts/
|	|	    	|	|--	account_info.html
|	|	    	|	|--	track_requests.html
|	|	    	|--	registrations/
|	|	    		|--	register.html
|	|------ __init__.py
|	|------ admin.py
|	|------ apps.py
|	|------ forms.py
|	|------ models.py
|	|------ tests.py
|	|------ urls.py
|	|------ views.py
|	|- gas_utility/
|	|		|--	__init__.py
|	|		|--	asgi.py
|	|		|--	settings.py
|	|		|--	urls.py
|	|		|--	views.py
|	|		|--	wsgi.py
|	|- media/
|	|		|--	attachments/
|	|				|-- My_Resume.pdf
|	|- utility_services/
|	|		|--	migrations/
|	|		|--	templates/
|	|		|	     |-- utility_services/
|	|		|	     |	        |--request_submitted.html
|	|		|	     |-- submit_request.html
|	|		|	     |-- track_request.html
|	|		|--	__init__.py
|	|		|--	admin.py
|	|		|--	apps.py
|	|		|--	forms.py
|	|		|--	models.py
|	|		|--	tests.py
|	|		|--	urls.py
|	|		|--	views.py
|	|- db.sqlite3
|	|- manage.py
|-README.md	