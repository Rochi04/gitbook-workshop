---
cover: >-
  https://images.unsplash.com/photo-1501386761578-eac5c94b800a?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwzfHxhdWRpZW5jZXxlbnwwfHx8fDE3MTc1ODI4MTd8MA&ixlib=rb-4.0.3&q=85
coverY: 0
---

# Users API

Here are the REST API endpoints for working with Users:

{% swagger src=".gitbook/assets/users.json" path="/user" method="post" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/createWithList" method="post" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/login" method="get" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/logout" method="get" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/{username}" method="get" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/{username}" method="put" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}

{% swagger src=".gitbook/assets/users.json" path="/user/{username}" method="delete" %}
[users.json](.gitbook/assets/users.json)
{% endswagger %}
