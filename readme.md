# Sample Kyverno policies

* Validation policies demonstrate the following usecases
  * [Enforcement of labels in workloads](validations/require-labels.yaml) demonstrates enforcement of existence of labels in deployments
  * [Enforcement of node selectors in workloads](validations/require-node-selector.yaml) demonstrates enforcement of providing a Node selector for workloads 

* [Mutations policy](mutations/prod.yaml) demonstrates creation of labels based on creating username and tier specified as node selector above

> Reference  
- [Kyverno sample policies](https://kyverno.io/policies/)