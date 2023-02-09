









gcloud container clusters create tuto-cluster --zone  europe-west1-b --machine-type e2-highmem-4




istioctl install


./kubectl-apply.sh -f


kubectl describe pods gateway-76654fc98d-89q9h -n store > gateway-pod-desc


kubectl apply -f addons/

kubectl port-forward svc/kiali -n istio-system 2001