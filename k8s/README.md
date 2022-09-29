
```bash
#create secret before

kubectl create secret generic pgpassword --from-literal=PGPASSWORD=topsecret --dry-run=client -o yaml
```