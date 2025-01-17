# Gas-Service-App
# Django application for Gas Utility Consumer Services

This project aims to provide a comprehensive consumer service platform for gas utility companies. The application enables customers to submit service requests, track their status, and view account details, while providing customer support representatives with tools to manage and resolve these requests efficiently.

## Structure of the Django application codebase

# gas_utility/
# |-- gas_utility/
# |     |-- __init__.py
# |     |-- settings.py
# |     |-- urls.py
# |     |-- wsgi.py
# |
# |-- customer/
# |     |-- migrations/
# |     |-- __init__.py
# |     |-- admin.py
# |     |-- apps.py
# |     |-- models.py
# |     |-- serializers.py
# |     |-- urls.py
# |     |-- views.py
# |
# |-- service_requests/
# |     |-- migrations/
# |     |-- __init__.py
# |     |-- admin.py
# |     |-- apps.py
# |     |-- models.py
# |     |-- serializers.py
# |     |-- urls.py
# |     |-- views.py
# |
# |-- templates/
# |     |-- customer/
# |     |     |-- customer_list.html
# |     |     |-- customer_detail.html
# |     |-- service_requests/
# |           |-- service_request_list.html
# |           |-- service_request_detail.html
# |
# |-- manage.py
