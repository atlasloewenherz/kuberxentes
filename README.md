# kuberxentes

Kubernetes Cluster built on the top of Ubuntu Xen DomUs using kubeadm ( a la bare metal)

# Creating the xen VM machines ()
xen-create-image --size=16Gb --hostname=cloud01 --netmask=255.255.255.0 --gateway=10.10.1.1
