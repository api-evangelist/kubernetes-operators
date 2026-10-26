# Kubernetes Operators (kubernetes-operators)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kubernetes Operators are a method of packaging, deploying, and managing Kubernetes applications that extend the Kubernetes API to create, configure, and manage instances of complex applications on behalf of a Kubernetes user.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Automation
- Cloud Native
- DevOps
- Infrastructure
- Kubernetes

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Kubernetes Operators

Kubernetes Operators extend the Kubernetes API for managing complex stateful applications using custom resources and controllers. An Operator encodes the operational knowledge of a domain expert into software that automates the deployment, scaling, and management of Kubernetes applications.

- **Human URL:** [https://kubernetes.io/docs/concepts/extend-kubernetes/operator/](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)

#### Tags

- Automation
- Cloud Native
- Custom Resources
- Kubernetes

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/)
- [AsyncAPI](asyncapi/kubernetes-operators-watch-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Kubernetes Custom Resource Definitions

The CustomResourceDefinition (CRD) API lets you extend the Kubernetes API by defining new resource types with custom schemas. When a CRD is created, the Kubernetes API server automatically serves and handles storage for the new custom resource, enabling operators and other controllers to manage domain-specific objects.

- **Human URL:** [https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)

#### Tags

- API Extension
- Cloud Native
- Custom Resources
- Kubernetes

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/custom-resource-definition-v1/)
- [Getting Started](https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/)
- [OpenAPI](openapi/kubernetes-crd-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/kubernetes-operator-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Operator SDK

The Operator SDK is a framework for building Kubernetes Operators in Go, Ansible, or Helm. It provides high-level APIs, abstractions, scaffolding tools, and CLI commands that simplify writing operator logic and integrating with the Operator Lifecycle Manager (OLM) for packaging and distribution.

- **Human URL:** [https://sdk.operatorframework.io/](https://sdk.operatorframework.io/)

#### Tags

- Go
- Kubernetes
- Operators
- SDK

#### Properties

- [Documentation](https://sdk.operatorframework.io/docs/overview/)
- [Getting Started](https://sdk.operatorframework.io/docs/building-operators/golang/tutorial/)
- [GitHub Repository](https://github.com/operator-framework/operator-sdk)

### Operator Lifecycle Manager

The Operator Lifecycle Manager (OLM) extends Kubernetes with a declarative API for installing, upgrading, and managing the lifecycle of Operators and their dependencies in a cluster. OLM provides cluster administrators with fine-grained control over what operators are available and which namespaces they can operate in.

- **Human URL:** [https://olm.operatorframework.io/](https://olm.operatorframework.io/)

#### Tags

- Cloud Native
- Kubernetes
- Lifecycle Management
- Operators

#### Properties

- [Documentation](https://olm.operatorframework.io/docs/)
- [GitHub Repository](https://github.com/operator-framework/operator-lifecycle-manager)
- [Changelog](https://github.com/operator-framework/operator-lifecycle-manager/releases)
- [OpenAPI](openapi/kubernetes-olm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### OperatorHub

OperatorHub.io is a community registry of Kubernetes Operators that can be discovered and installed via the Operator Lifecycle Manager. It provides a catalog of operators across categories including databases, monitoring, security, and networking for use in Kubernetes clusters.

- **Human URL:** [https://operatorhub.io/](https://operatorhub.io/)

#### Tags

- Community
- Kubernetes
- Operators
- Registry

#### Properties

- [Documentation](https://operatorhub.io/)

### Controller-Runtime

controller-runtime is a set of Go libraries for building Kubernetes controllers and operators. It is used by both Kubebuilder and Operator SDK and provides core abstractions including Manager, Client, Cache, and Reconciler interfaces for building controllers that interact with the Kubernetes API.

- **Human URL:** [https://github.com/kubernetes-sigs/controller-runtime](https://github.com/kubernetes-sigs/controller-runtime)

#### Tags

- Controllers
- Go
- Kubernetes
- SDK

#### Properties

- [Documentation](https://pkg.go.dev/sigs.k8s.io/controller-runtime)
- [GitHub Repository](https://github.com/kubernetes-sigs/controller-runtime)

## Common Properties

- [Website](https://kubernetes.io)
- [Documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/)
- [Getting Started](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [GitHub Organization](https://github.com/operator-framework)
- [GitHub Repository](https://github.com/operator-framework/operator-sdk)
- [Blog](https://kubernetes.io/blog/)
- [Community](https://kubernetes.io/community/)
- [Changelog](https://kubernetes.io/releases/)
- [JSON Schema](json-schema/kubernetes-operator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kubernetes-operators-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
