===============================================
	1. Manual Approval Before Deploy to the container.
	2. Post Build Block in the pipeline. Failed,Success,Unstable,Abort etc..
	3. Cleanup In the Post action block in jenkins pipeline.
	4. Create New Item ; Create a docker image and push/commit to remote registry.eg; AWS ACR,ECR…
	5. Create New Item; Deploy into new docker host machine and pull image from the remote Registry.Verify the application is up and running .
	6. Create new index.html then automatically push to registry and deploy to docker container.
	7. Create a jenkins agent machine and include in the jenkins pipeline new agent.
	8. Email Notification with jenkins pipeline . Sent an status notification once pipeline completed.
	9. Create a backup task using jenkins pipeline.
	10. Create users and Give the permission based on project matrix individually.
===============================================