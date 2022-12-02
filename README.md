
# test2
blah blah blah

## To run the app:

``npm run build``
``npm run start``

## Usage example:
### to get help message:
``curl localhost:8080/help``
### to convert xml to json:
``curl localhost:8080/xml-to-json -d '<foo attr="value">bar</foo>'``
### to convert json to xml:
``curl localhost:8080/json-to-xml -d '{"foo":{"attr":"value","$t":"bar"}}'``

## Docker:
### Build image:
``docker build . -t converter``
### Run image:
``docker run -p 8080:8080 converter``

# test2
blah blah blah

## To run the app:

``npm run build``
``npm run start``

## Usage example:
### to get help message:
``curl localhost:8080/help``
### to convert xml to json:
``curl localhost:8080/xml-to-json -d '<foo attr="value">bar</foo>'``
### to convert json to xml:
``curl localhost:8080/json-to-xml -d '{"foo":{"attr":"value","$t":"bar"}}'``

## Docker:
### Build image:
``docker build . -t converter``
### Run image:
``docker run -p 8080:8080 converter``
