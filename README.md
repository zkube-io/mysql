# mysql image file for zkube.

# Usage:

## thru github:
1) Create your account on zkube.io
2) Create a namespace and secret-key
3) Set your gitflow automated deploy...
Into your zkube.deploy.yml

```
version: 0.01
type: Deploy
namespace: "YOUR-NAMESPACE"   
secretKey: "YOUR-SECRET-KEY"
deploys:
    - name: DB
      slug: "mysql"
      image: https://github.dev/zkube-io/mysql             
```

And you have a mysql up and running!

## manually
1) Create your account on zkube.io
2) Create a namespace and secret-key
3) Click on "create deploy", "source" and paste this code:
```
version: 0.01
type: Deploy
namespace: "YOUR-NAMESPACE"   
secretKey: "YOUR-SECRET-KEY"
deploys:
    - name: DB
      slug: "mysql"
      image: https://github.dev/zkube-io/mysql             
```






