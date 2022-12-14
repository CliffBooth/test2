main branch [![Tests](https://github.com/CliffBooth/test2/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/CliffBooth/test2/actions/workflows/test.yml)

develop branch [![Tests](https://github.com/wooffie/converter/actions/workflows/gradle-tests.yml/badge.svg?branch=master)](https://github.com/wooffie/converter/actions/workflows/gradle-tests.yml)


# test2
blah blah blah

## To run the app:

``npm run install``

``npm run build``

``npm run start``

## Usage example:
### to get help message:
``curl localhost:8080/help``
### to convert xml to json:
``curl localhost:8080/xml-to-json -d "<foo attr=\"value\">bar</foo>"``
### to convert json to xml:
``curl localhost:8080/json-to-xml -d '{"foo":{"attr":"value","$t":"bar"}}``

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
