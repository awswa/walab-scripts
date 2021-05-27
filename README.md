# walab-scripts

### getIDtoken.py helps you generate ID token using Amazon Cognito User Pools.

Please refer to the following format:
```sh
python getIDtoken.py <username> <user_password> <user_pool_id> <app_client_id> <app_client_secret>
```


### sendRequest.py helps send http request with ID token.

Please refer to the following format:
```sh
python sendRequest.py <URL> <ID_Token>
```
