# Core Concepts (13%)

## Practice questions based on these concepts

* Understand Kubernetes API Primitives
* Create and Configure Basic Pods

## Questions

<details><summary>List all the namespaces in the cluster</summary>
<p>

```
k get ns
k get -A ns

```
</p>
</details>

<details><summary>List all the pods in all namespaces</summary>
<p>

```
k get po -A
```
</p>
</details>

<details><summary>List all the pods in the particular namespace</summary>
<p>

```
k get po -n <namespace name>
```
</p>
</details>

<details><summary>List all the services in the particular namespace</summary>
<p>

```

```
</p>
</details>

<details><summary>List all the pods showing name and namespace with a json path expression</summary>
<p>

```

```
</p>
</details>

<details><summary>Create an nginx pod in a default namespace and verify the pod running</summary>
<p>

```

```
</p>
</details>


<details><summary>Create the same nginx pod with a yaml file</summary>
<p>

```

```
</p>
</details>


<details><summary>Output the yaml file of the pod you just created</summary>
<p>

```

```
</p>
</details>


<details><summary>Output the yaml file of the pod you just created without the cluster-specific information</summary>
<p>

```

```
</p>
</details>


<details><summary>Get the complete details of the pod you just created</summary>
<p>

```

```
</p>
</details>


<details><summary>Delete the pod you just created</summary>
<p>

```


```
</p>
</details>


<details><summary>Delete the pod you just created without any delay (force delete)</summary>
<p>

```

```
</p>
</details>


<details><summary>Create the nginx pod with version 1.17.4 and expose it on port 80</summary>
<p>

```

```
</p>
</details>


<details><summary>Change the Image version to 1.15-alpine for the pod you just created and verify the image version is updated</summary>
<p>

```

```
</p>
</details>


<details><summary>Change the Image version back to 1.17.1 for the pod you just updated and observe the changes</summary>
<p>

```

```
</p>
</details>


<details><summary>Check the Image version without the describe command</summary>
<p>

```

```
</p>
</details>


<details><summary>Create the nginx pod and execute the simple shell on the pod</summary>
<p>

```

```
</p>
</details>


<details><summary>Get the IP Address of the pod you just created</summary>
<p>

```

```
</p>
</details>

<details><summary>Create a busybox pod and run command ls while creating it and check the logs</summary>
<p>

```

```
</p>
</details>


<details><summary>If pod crashed check the previous logs of the pod</summary>
<p>

```

```
</p>
</details>


<details><summary>Create a busybox pod with command sleep 3600</summary>
<p>

```

```
</p>
</details>


<details><summary>Check the connection of the nginx pod from the busybox pod</summary>
<p>

```

```
</p>
</details>


<details><summary>Create a busybox pod and echo message ‘How are you’ and delete it manually</summary>
<p>

```

```
</p>
</details>


<details><summary>Create a busybox pod and echo message ‘How are you’ and have it deleted immediately</summary>
<p>

```

```
</p>
</details>


<details><summary>Create an nginx pod and list the pod with different levels of verbosity</summary>
<p>

```

```
</p>
</details>


<details><summary>List the nginx pod with custom columns POD_NAME and POD_STATUS</summary>
<p>

```

```
</p>
</details>


<details><summary>List all the pods sorted by name</summary>
<p>

```

```
</p>
</details>


<details><summary>List all the pods sorted by created timestamp</summary>
<p>

```

```
</p>
</details>
