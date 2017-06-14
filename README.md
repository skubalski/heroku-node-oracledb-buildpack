# heroku-node-oracledb-buildpack
Dependencies:
- [heroku-buildpack-apt](https://github.com/heroku/heroku-buildpack-apt.git)
  - jq
  - libaio1
- ``oracle.json`` - contains driver's paths
  - sdk.path - path to SDK zip package
  - basic.path - path to BASIC zip package
  - tns_path - tns config path
