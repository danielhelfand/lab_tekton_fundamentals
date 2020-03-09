In this self-paced tutorial, you will learn how to use Tekton to automate the deployment of applications 
to Kubernetes.

Here are some of the things you will get to do during this workshop:

* Learn about the [custom resource definitions](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/) (CRDs) behind Tekton
* Create a CI/CD pipeline using Tekton CRDs on a Kubernetes cluster via the Kubernetes CLI (`kubectl`) and the Tekton CLI (`tkn`)
* Deploy an application to a Kubernetes cluster via a Tekton CI/CD pipeline
* View your deployed application 
* Learn more about the Tekton project as a whole and additional resources for the project
* Explore! You have a Kubernetes cluster with Tekton and associated tools installed. Have fun with it and use it to do things beyond what the workshop suggests when you finish.

Before beginning the workshop, you should learn a little about the workshop environment. 

All commands in this tutorial can be executed by clicking the running stick figure icon on the side of the command. Go 
ahead and run the following command to see the version of `kubectl`/Kubernetes available during this workshop:

```execute-1 
kubectl version --short
```

Note that there will be times a command is run in the bottom terminal as opposed to the top terminal. For the `tkn` command 
below, when you run it, it will execute in the lower terminal: 

```execute-2 
tkn version
```

Where the command is executed is denoted by the number with the running stick figure icon. If there is a 1, the command will 
execute in the top terminal. If there is a 2, the command will execute in the bottom terminal. 

The last piece of information to note about the workshop environment is the **Console** tab in the top center of your browser 
next to the **Terminal** tab. The **Console** tab provides the Kubernetes dashboard to help you visualize your Kubernetes cluster 
during the workshop. You will occassionally be asked to switch over to this view to highlight a particular concept. 

Go ahead and click on the **Console** tab to take a look at the Kubernetes dashboard. Whenever you are done looking at the **Console** 
tab, switch back to the **Terminal** tab by clicking on it. 

Before beginning the workshop, execute the following commands to clear your terminals:

```execute-1 
clear
```

```execute-2
clear
```