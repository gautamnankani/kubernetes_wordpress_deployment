It will deploy the whole setup for wordpress server on kubernetes

(I used minikube VM, so it will be perfect if you want to test this code, 
other cluster may need some changes in pvc, as sc was already present in minikube so i used it
but it totally depends on you what storage you want to use)

use command:

**kubectl create -k .**

To browse:   node-ip:30000
