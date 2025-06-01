# saas-auth-wall-of-shame

these are services that can be used to connect to clouds like AWS but do not natively support temporary access using roles and so Users and Access Tokens are needed which is a risk if those tokens ever leak.

1. tray.io aws integration
    - has a custom AWS integration that does support a session token which can be used with a temporary role
    - AWS bedrock integration only supports access key and secret id
    - TODO: source link
1. netlify
    - TODO: source link
1. rapid7
    - TODO: source link
