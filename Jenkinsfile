def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/mule/mule-3.5.x" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "mavenAdditionalArgs" : "-Djarsigner.skip" ]

runtimeProjectsBuild(pipelineParams)