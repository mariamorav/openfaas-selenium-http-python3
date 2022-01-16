# OpenFaaS Python 3.8 with selenium Template

OpenFaas python3.8 flask template with selenium support.

## Usage

```
faas-cli template pull https://github.com/mariamorav/openfaas-selenium-http-python3

faas-cli new --lang selenium-python3-http <function_name> --prefix <registry>

faas-cli up -f <function_name>.yml
```