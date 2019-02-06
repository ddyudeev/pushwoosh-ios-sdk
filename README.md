# Initial page

## Getting Super Powers

I mean ok let me see what's happening here.

I do rather dislike that it doesn't seem to be possible to use infoblocks from here.

hyperlink!

{% api-method method="get" host="https://pushwoosh.com/json/testMethod" path="" %}
{% api-method-summary %}
Important Method for the program
{% endapi-method-summary %}

{% api-method-description %}
This method retrieves the parameter and passes it to the **function**
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="parameter1" type="array" required=true %}
parameter for **main** function
{% endapi-method-parameter %}

{% api-method-parameter name="parameter2" type="object" required=false %}
optional parameter for main function  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
200 is ~~_very_~~ good for your **health**
{% endapi-method-response-example-description %}

```
Response is good if the parameter has been passed successfully
{
    json:true
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=302 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
Moved somewhere
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

