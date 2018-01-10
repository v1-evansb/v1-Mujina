# Script usage

All RESTful API calls will be made against the Mock IDP @
http://localhost:8080 unless otherwise specified

## addUser.sh
```bash
sh addUser.sh user password
```

_With a custom Mock IDP_
```bash
sh addUser.sh user password http://some-idp-host:8080
```


## setAttribute.sh
```bash
sh setAttribute.sh foo bar
```

_With a custom Mock IDP_
```bash
sh setAttribute.sh foo bar http://some-idp-host:8080
```


## delAttribute.sh
```bash
sh delAttribute.sh foo
```

_With a custom Mock IDP_
```bash
sh delAttribute.sh foo http://some-idp-host:8080
```


## resetIDP.sh
```bash
sh resetIDP.sh
```

_With a custom Mock IDP_
```bash
sh resetIDP.sh http://some-idp-host:8080
```
