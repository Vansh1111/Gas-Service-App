
# Django application for Gas Utility Consumer Services

This project aims to provide a comprehensive consumer service platform for gas utility companies. The application enables customers to submit service requests, track their status, and view account details, while providing customer support representatives with tools to manage and resolve these requests efficiently.

# Django application for Gas Utility Consumer Services

This project aims to provide a comprehensive consumer service platform for gas utility companies. The application enables customers to submit service requests, track their status, and view account details, while providing customer support representatives with tools to manage and resolve these requests efficiently.

Structure of the Django application codebase <br/>
|-- gas_utility/ <br/>
|     |-- __init__.py <br/>
|     |-- settings.py <br/>
|     |-- urls.py <br/>
|     |-- wsgi.py <br/>
|<br/>
|-- customer/ <br/>
|     |-- __init__.py <br/>
|     |-- admin.py <br/>
|     |-- apps.py <br/>
|     |-- models.py <br/>
|     |-- serializers.py <br/>
|     |-- urls.py <br/>
|     |-- views.py <br/>
|<br/>
|-- service_requests/ <br/>
|     |-- __init__.py <br/>
|     |-- admin.py <br/>
|     |-- apps.py <br/>
|     |-- models.py <br/>
|     |-- serializers.py <br/>
|     |-- urls.py <br/>
|     |-- views.py <br/>
| <br/>
|-- templates/ <br/>
|     |-- customer/ <br/>
|     |     |-- customer_list.html <br/>
|     |     |-- customer_detail.html <br/>
|     |-- service_requests/ <br/>
|           |-- service_request_list.html <br/>
|           |-- service_request_detail.html <br/>
|<br/>
|-- manage.py <br/>
