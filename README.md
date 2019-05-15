# How to setup your signature template


## Fileds available

Here the list of fields available for your template :
EMAIL, FIRSTNAME, LASTNAME, TITLE, COMPANY, COSTCENTER, DEPARTMENT, WORKPHONE, MOBILEPHONE, WORKADRESS, CUSTOM1, CUSTOM2, CUSTOM3, CUSTOM4, CUSTOM5

You have 5 customs fields in order to add some specific data.


## How to use the fields

In your template you must specifiy the paramater like this : {{XXXXXXX}}

Name Fields must be used respecting the exact name of the column header. For example for EMAIL you must use the parameter {{EMAIL}}.

{{email}}, {{Email}}, {{mail}} are not valid.


## Dynamics fields

In order to have some conditionnal data in your template you can use Dynamics Fields, syntax is : {{(Conditional data)EMAIL}}

For example conditional fields are interesting for phone number, if you want to add a phone icon before the phone number you can set the icon as conditional data. In this case if a phone number exist the icon is displayed if phone number is not present for user it is not displayed.

Example : {{(<img src="https://www……" valign="middle">)mobilePhone}}
