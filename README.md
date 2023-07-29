# k3d
K3d-full-tested
# 1. Docker, Kubectl & K3d installation from k3d-installation.txt file.
# 2. Create K3d cluster from config.yaml file
$ k3d cluster create --config config.yaml
# 3. Deploy mysql in k3d cluster and volume mount on local-host-machine
# 4. Deploy keycloak in k3d cluster and volume mount on local-host-machine. Keycloak connect with mysql db and keycloak deployment with-hostname or without-hostname.
# 5. Deploy Kong-ingress-controler and kong-ingress.
