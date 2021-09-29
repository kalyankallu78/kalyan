# kalyan
import re
alphanum_value=input("enter the value")
if re.match('^[A-Za-z0-9!@#$%]{2,10}$',alphanum_value):
    print('its valid match')
else:
    print('not valid')
