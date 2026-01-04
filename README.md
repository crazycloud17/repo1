containers:
...
- name: order-service
  image: <acrName>.azurecr.io/aks-store-demo/order-service:latest
...
- name: product-service
  image: <acrName>.azurecr.io/aks-store-demo/product-service:latest
...
- name: store-front
  image: <acrName>.azurecr.io/aks-store-demo/store-front:latest
  
