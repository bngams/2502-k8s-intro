/!\ à l'utilisation des commandes impératives dans le namespace
kubectl exec -it mypod -n mynamespaceexercice1 -c mycontainer-1 -- /bin/sh -c "echo 'Helloworld from Kube' > /usr/share/nginx/html/i
ndex.html"
