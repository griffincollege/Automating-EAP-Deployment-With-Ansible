# alternatives_to_docker_webinar
## Commands To Run
1. ansible-galaxy install -r roles/requirements
2. ansible-playbook deployment_workflow.yaml -i inventory/ -e image_registry=<your image registry>

## NOTE
These playbooks and this repository are a work in progress and may need configuration to work according to your use cases.
