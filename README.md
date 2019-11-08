# Kubeflow-Custom-Dockerfiles
Custom docker files for use with kubeflow / kubernetes

I was unable to find dockerfiles that work out of the box for custom images when creating a workflow in kubeflow so I made my own based on nvidia ngc pytorch image and the templates provided by kubeflow for different tensorflow implementations.  Additionally, permissions have been fixed so that the default "jovyan" username has admin privleges and ownership over conda in the base implementation - this results in having the ability to install in notebooks served from kubeflow setups.
