<pre>
apiVersion: v1
kind: LimitRange
metadata:
  name: low-res
spec:
  limits:
  - default:
      cpu: 1
      memory: 500Mi
    defaultRequest:
      cpu: .5
      memory: 100Mi
    type: Container
</pre>
