# functions-from-zero
live training

[![Python application test with Github Actions](https://github.com/vincenzosilvio/functions-from-zero/actions/workflows/main.yml/badge.svg)](https://github.com/vincenzosilvio/functions-from-zero/actions/workflows/main.yml)


### To call Microservice

'''bash
curl -X 'POST' \
  'https://psychic-umbrella-4wjqj464v7425rpj-8080.app.github.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
'''

### Build container

'docker build .'
'docker image ls'

### Run container

'docker run -p 127.0.0.1:8080:8080 imageID'

### Invoke post request

run 'bash invoke.sh'