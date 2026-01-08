resources = create_gcp_resources(project, fast=True)
log(resources)
deploy(project, resources)


