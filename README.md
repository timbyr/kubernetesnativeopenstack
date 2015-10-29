heat stack-create -f k8s.yaml -P discoveryurl=$(curl -s https://discovery.etcd.io/new) -P key="$(cat key.pub)"  test
