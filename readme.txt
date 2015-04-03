Sample curl commands:

# List all the widget resources as json
curl -v -H "Accept: application/json" http://localhost:8100/widgets

# List all the widget resources as html.
curl -v -H "Accept: text/html" http://localhost:8100/widgets

# List widget "1" resource as json
curl -v -H "Accept: application/json" http://localhost:8100/widgets/1

# update widget "1" with a new name
curl -v -H "Accept: application/json" -X PUT -d "id=1&name=my updated name" http://localhost:8100/widgets/1

# create a new widget resource
curl -v -X POST -d "name=a dandy new widget" http://localhost:8100/widgets  
   
# delete widget "1"
curl -v -X DELETE http://localhost:8100/widgets/1



