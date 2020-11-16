```sh

#!/bin/bash

read -p "Please enter location" LOCATION

if [ $LOCATION = "USA" ]
then
  echo "Access Granted"
elif [ $LOCATION = "INDIA" ]
then
  echo "Access Granted"
else
  echo "Please contact your admin"
fi
```
