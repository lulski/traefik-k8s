# traefik-k8s
traefik practice

> get nodeport number using

```bash
kubectl describe svc traefik-ingress-servic
```

http://lulski.localhost:32158/dashboard/

http://whoami.localhost:32158/

todo: what made these special?
  kind: Service
    spec:
      type: NodePort 