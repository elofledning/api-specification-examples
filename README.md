# api-specification-examples
Asyncapi and OpenAPI specification examples


# OpenAPi example openapi-travellers.yml
View the openapi example on Swagger Editor here: https://editor.swagger.io/ (copy-paste the YAML to view markup)



# AsyncAPI example async-travellers.yml
View the asyncapi example on Playground here: https://playground.asyncapi.io/ (copy-paste the YAML to view markup)

Example is using test MQTT server/broker at https://test.mosquitto.org/ 
1. Install node package for code generation: ```npm install -g @asyncapi/generator```
2. Generate node.js code ```ag asyncapi-travellers.yml @asyncapi/nodejs-template -o output -p server=mosquitto```


