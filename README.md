

# eticaret.proto
## proto files for eticaret services


use this repository to provide .proto files for .backend.* services


## services port definitions (Local)

- Product Service :5000
- Event Service :5001

***Please update ports if a service added or changed***

## eticaret.backend.node

## delete old proto files

#### unix & macos
```shell
rm -r libs/proto
````

#### windows

```shell
Remove-Item –path $pwd/libs/proto –recurse
```

## Get new proto files

backend.node

Make sure node.16 or later installed on machine to use npx command
```shell 
npx degit https://github.com/takimbirprojeler/eticaret.proto libs/proto
```
