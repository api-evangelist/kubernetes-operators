# Kubernetes Operators (kubernetes-operators)
Kubernetes Operators are a method of packaging, deploying, and managing Kubernetes applications that extend the Kubernetes API to create, configure, and manage instances of complex applications on behalf of a Kubernetes user.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Kubernetes, Automation, Infrastructure, DevOps, Cloud Native

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-04-28 

## APIs

### Kubernetes Operators
Kubernetes Operators extend the Kubernetes API for managing complex stateful applications using custom resources and controllers. An Operator encodes the operational knowledge of a domain expert into software that automates the deployment, scaling, and management of Kubernetes applications.

**Human URL:** [https://kubernetes.io/docs/concepts/extend-kubernetes/operator/](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)


#### Tags:

 - Kubernetes, Custom Resources, Automation, Cloud Native

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/)
- [AsyncAPI](asyncapi/kubernetes-operators-watch-asyncapi.yml)

### Kubernetes Custom Resource Definitions
The CustomResourceDefinition (CRD) API lets you extend the Kubernetes API by defining new resource types with custom schemas. When a CRD is created, the Kubernetes API server automatically serves and handles storage for the new custom resource, enabling operators and other controllers to manage domain-specific objects.

**Human URL:** [https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)


#### Tags:

 - Kubernetes, Custom Resources, API Extension, Cloud Native

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/custom-resource-definition-v1/)
- [Getting Started](https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/)
- [OpenAPI](openapi/kubernetes-crd-openapi.yml)
- [JSONSchema](json-schema/kubernetes-operator-schema.json)

### Operator SDK
The Operator SDK is a framework for building Kubernetes Operators in Go, Ansible, or Helm. It provides high-level APIs, abstractions, scaffolding tools, and CLI commands that simplify writing operator logic and integrating with the Operator Lifecycle Manager (OLM) for packaging and distribution.

**Human URL:** [https://sdk.operatorframework.io/](https://sdk.operatorframework.io/)


#### Tags:

 - Kubernetes, Operators, SDK, Go

#### Properties

- [Documentation](https://sdk.operatorframework.io/docs/overview/)
- [Getting Started](https://sdk.operatorframework.io/docs/building-operators/golang/tutorial/)
- [GitHubRepository](https://github.com/operator-framework/operator-sdk)

### Operator Lifecycle Manager
The Operator Lifecycle Manager (OLM) extends Kubernetes with a declarative API for installing, upgrading, and managing the lifecycle of Operators and their dependencies in a cluster. OLM provides cluster administrators with fine-grained control over what operators are available and which namespaces they can operate in.

**Human URL:** [https://olm.operatorframework.io/](https://olm.operatorframework.io/)


#### Tags:

 - Kubernetes, Operators, Lifecycle Management, Cloud Native

#### Properties

- [Documentation](https://olm.operatorframework.io/docs/)
- [GitHubRepository](https://github.com/operator-framework/operator-lifecycle-manager)
- [Change Log](https://github.com/operator-framework/operator-lifecycle-manager/releases)
- [OpenAPI](openapi/kubernetes-olm-openapi.yml)

### OperatorHub
OperatorHub.io is a community registry of Kubernetes Operators that can be discovered and installed via the Operator Lifecycle Manager. It provides a catalog of operators across categories including databases, monitoring, security, and networking for use in Kubernetes clusters.

**Human URL:** [https://operatorhub.io/](https://operatorhub.io/)


#### Tags:

 - Kubernetes, Operators, Registry, Community

#### Properties

- [Documentation](https://operatorhub.io/)

### controller-runtime
controller-runtime is a set of Go libraries for building Kubernetes controllers and operators. It is used by both Kubebuilder and Operator SDK and provides core abstractions including Manager, Client, Cache, and Reconciler interfaces for building controllers that interact with the Kubernetes API.

**Human URL:** [https://github.com/kubernetes-sigs/controller-runtime](https://github.com/kubernetes-sigs/controller-runtime)


#### Tags:

 - Kubernetes, Go, Controllers, SDK

#### Properties

- [Documentation](https://pkg.go.dev/sigs.k8s.io/controller-runtime)
- [GitHubRepository](https://github.com/kubernetes-sigs/controller-runtime)

## Common Properties

- [Website](https://kubernetes.io)
- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/)
- [Getting Started](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [GitHub Organization](https://github.com/operator-framework)
- [GitHubRepository](https://github.com/operator-framework/operator-sdk)
- [Blog](https://kubernetes.io/blog/)
- [Community](https://kubernetes.io/community/)
- [Change Log](https://kubernetes.io/releases/)
- [JSONSchema](json-schema/kubernetes-operator-schema.json)
- [JSON-LD](json-ld/kubernetes-operators-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
