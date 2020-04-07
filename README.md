# concoursesp

The set_pipeline step was introduced in Concourse v5.8.2. It is considered an experimental feature until its associated https://github.com/concourse/rfcs/pull/31 is resolved.

1. `fly -t local sp -p concoursesp -c pipeline.yaml -n`
2. uncomment the second job in https://github.com/gowrisankar22/concoursesp/blob/master/ci/pipeline.yml and do that commit. Now you can see pipeline sets the pipeline itself.
