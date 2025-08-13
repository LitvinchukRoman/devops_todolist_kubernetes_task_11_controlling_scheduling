To test, you should run the script bootstrap.sh:
```
bash bootstrap.sh
```
Then all Kubernetes objects will be applied.

To test run:
```
kubectl get pods -n mysql -o wide
```
If all pods are present, then it works properly