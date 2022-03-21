# Katib confip-map
## This is an example of storing trial templates within one config map.
#### It can be added to the k8s cluster and those different templates of (k8s job, TFJob, PyTorchJob, etc) could be automatically recognized by webhook while creating Katib experiment with *kubectl create -f exp_config.yaml*