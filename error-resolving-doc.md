# Steps were taken for resolving errors during development processß

### [1] resolved issue with errors package version https://github.com/moby/moby/issues/46987
### errors package was migrated from v0.8.1 to v0.9.1 due to a bug occured in docker clients -> docker incompatible package

### [2] issue with docker api version resolved as https://stackoverflow.com/questions/62079794/error-response-from-daemon-client-version-1-40-is-too-new-maximum-supported-ap. command for fixing docker api version is described below
    export DOCKER_API_VERSION=1.41

### [3] 
`Error response from daemon: invalid restart policy 'test-container-1'`
