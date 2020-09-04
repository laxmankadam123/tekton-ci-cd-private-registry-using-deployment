# tekton-ci-cd-private-registry
Following are the steps to deploy ci/cd using tekton

1. first create the persistent volume and persistent volume claim for registry container for that use pv.yaml and pvc.yaml file.

2. in second step create deployment for registry and registryui for that use registry.yaml registryui.yaml file.

3. create serviceaccount for that use svc.yaml file.

4. create pipelineresources for that use pipelineresource.yaml file.

5. create task task-build for that use task-build.yaml file.

6. create task task-deploy for that use task-deploy.yaml file.

7. create pipeline for that use pipeline.yaml file.

8. before creating the pipelinerun update the changes in to they deploy.yaml file and mention the name of image you pushed in to they registry.

9. create pipelinerun for that use pipelinerun.yaml file.
