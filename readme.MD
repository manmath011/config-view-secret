
kubectl create configmap configmap1 --from-literal=name=first-configmap
1992  minikube start
1993  kubectl create configmap configmap1 --from-literal=name=first-configmap
1994  ls
1995  kubectl apply -f cm-1.yml
1996  kubectl get pods
1997  kubectl exec -it congigmap-demo1 -- printenv
1998  kubectl exec -it configmap-demo1 -- printenv
1999  kubectl describe pod configmap-demo1
2000  minikube dashboard
2001  kubectl describe pod configmap-demo1
2002  kubectl exec -it configmap-demo1 -- printenv
2003  kubectl get pods
2004  kubectl get logs configmap-demo1
2005  kubectl logs configmap-demo1
2006  kubectl describe pod configmap-demo1
2007  kubectl get configmaps
2008  kubectl delete pod configmap-demo1
2009  kubectl apply -f cm-1.yml
2010  kubectl get pods
2011  kubectl exec -it configmap-demo1 -- printenv
2012  kubectl create configmap configmap-2 --from-literal=name=second-configmap
2013  kubectl get configmaps
2014  kubectl delete configmap configmap-2
2015  kubectl create configmap configmap-2 --from-literal=name=second-configmap --from-literal=color=blue
2016  kubectl get configmaps
2017  kubectl apply -f cm-2.yml
2018  kubectl get pods
2019  kubectl get cm
2020  kubectl exec -it configmap-demo-2 -- printenv
2021  kubectl create configmap-3 --from-file=data-file
2022  kubectl create configmap configmap-3 --from-file=data-file
2023  kubectl get cnf
2024  kubectl get cn
2025  kubectl get cm
2026  kubectl apply -f cm-3.yml
2027  kubectl get pods
2028* kubectl exec -it configma3 -- bash
2029  kubectl describe cm configmap-3
2030  kubectl describe cm configmap-2
2031  kubectl describe cm configmap1
2032  kubectl get cm
2033  kubectl create secret generic db-secret --from-literal=username=dbuser --from-literal=password=Y4nys7f11
2034  kubectl get secret
2035  kubectl describe db-secret
2036  kubectl describe secret db-secret
2037  kubectl apply -f secret1.yml
2038  cd secret
  
</html>
```

This HTML code creates a simple webpage that displays your `kubectl` commands in a nicely formatted way. You can copy this code into an HTML file and open it in your browser to see the result. Let me know if you need any modifications!
