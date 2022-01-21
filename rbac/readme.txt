
kubectl create serviceaccount my-sa-app -n <NAMESPACE>

kubectl describe serviceaccount my-sa-app -n <NAMESPACE>

kubectl describe secret <tokenName> -n <NAMESPACE>

kubectl apply -f deployment.yaml -n <NAMESPACE>
