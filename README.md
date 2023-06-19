# http3_client
## http3 compatible module that can be handled like requests
This module supports http3!
## Install
```
pip3 install https://github.com/dmnstnd/http3client/releases/download/1.0.0/http3_client-1.0.0.whl
```
## How to use?
```python3
import http3_client as requests
print(requests.get("https://google.com/").status_code)
// -> 200
```
