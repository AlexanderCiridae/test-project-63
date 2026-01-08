try
    resources = create_gcp_resources(project, fast=True)
    log(resources)
    deploy(project, resources)
catch e
    handle_errors(e)

