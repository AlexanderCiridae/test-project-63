try
    resources = create_gcp_resources(project)
    log(resources)
    deploy(project, resources)
catch e
    handle_errors(e)


