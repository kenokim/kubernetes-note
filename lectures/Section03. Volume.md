# Volume
## PV/PVC
- Volume : Local, git, AWS NFS
- Persistent volume : volume 을 대상으로 정의한 오브젝터
```yml
kind: PersistentVolume
spec:
  nfs:
    server: 192.168.0.xxx
    path: /sda/data
  iscsi
...
```
