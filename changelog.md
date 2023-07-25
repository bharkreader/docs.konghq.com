# Changelog

## Week 29

### [Resolve DOCU-1791. Clarify db-backed instances only.](https://github.com/Kong/docs.konghq.com/pull/5834) (2023-07-21)

Added an important note to clarify that the license report functionality cannot be run on DB-less deployments, it is only meant for database-backed deployments per [DOCU-1791](https://konghq.atlassian.net/browse/DOCU-1791).

## Modified

- https://docs.konghq.com/gateway/3.0.x/licenses/report
- https://docs.konghq.com/gateway/3.1.x/licenses/report
- https://docs.konghq.com/gateway/3.2.x/licenses/report
- https://docs.konghq.com/gateway/3.3.x/licenses/report


### [Fix cookie_domain example](https://github.com/Kong/docs.konghq.com/pull/5832) (2023-07-21)

The cookie_domain example in the docs has a minor "typo".

## Modified

- https://docs.konghq.com/gateway/3.0.x/install/kubernetes/openshift
- https://docs.konghq.com/gateway/3.1.x/install/kubernetes/openshift
- https://docs.konghq.com/gateway/3.2.x/install/kubernetes/openshift
- https://docs.konghq.com/gateway/3.3.x/install/kubernetes/openshift
- https://docs.konghq.com/enterprise/2.1.x/deployment/installation/kong-on-kubernetes
- https://docs.konghq.com/enterprise/2.2.x/deployment/installation/kong-on-kubernetes
- https://docs.konghq.com/enterprise/2.3.x/deployment/installation/kong-on-kubernetes
- https://docs.konghq.com/enterprise/2.4.x/deployment/installation/kong-on-kubernetes
- https://docs.konghq.com/enterprise/2.5.x/deployment/installation/kong-on-kubernetes
- https://docs.konghq.com/gateway/2.6.x/install-and-run/helm
- https://docs.konghq.com/gateway/2.6.x/install-and-run/openshift
- https://docs.konghq.com/gateway/2.7.x/install-and-run/helm
- https://docs.konghq.com/gateway/2.7.x/install-and-run/openshift
- https://docs.konghq.com/gateway/2.8.x/install-and-run/helm
- https://docs.konghq.com/gateway/2.8.x/install-and-run/openshift


### [Update enable-rbac.md](https://github.com/Kong/docs.konghq.com/pull/5830) (2023-07-20)

negative=true flag should be indicated for the curl command for these examples here as negative=false is set by default without specific indication




--data negative=true flag was left out in this example

## Modified

- https://docs.konghq.com/gateway/3.0.x/production/access-control/enable-rbac
- https://docs.konghq.com/gateway/3.1.x/production/access-control/enable-rbac
- https://docs.konghq.com/gateway/3.2.x/production/access-control/enable-rbac
- https://docs.konghq.com/gateway/3.3.x/production/access-control/enable-rbac


### [Move plugin how-tos into their respective plugin docs](https://github.com/Kong/docs.konghq.com/pull/5828) (2023-07-19)

Make plugin how-to docs more discoverable by putting them where the plugins are. 
Rewriting + bringing a bunch of the content up to date.

Combining content wherever it's duplicate. Note that I didn't do a thorough copyedit here, just a top-level skim.

This PR covers the following plugins, which were previously in the Kong Gateway section:
* Response Transformer
* GraphQL plugins
* gRPC plugins

Also splitting the target plugins' overviews into proper how-to docs to make room for this info.

## Added

- https://docs.konghq.com/hub/kong-inc/graphql-proxy-cache-advanced/
- https://docs.konghq.com/hub/kong-inc/graphql-proxy-cache-advanced/how-to/
- https://docs.konghq.com/hub/kong-inc/graphql-rate-limiting-advanced/
- https://docs.konghq.com/hub/kong-inc/graphql-rate-limiting-advanced/how-to/
- https://docs.konghq.com/hub/kong-inc/grpc-gateway/how-to/
- https://docs.konghq.com/hub/kong-inc/grpc-web/how-to/
- https://docs.konghq.com/hub/kong-inc/request-transformer-advanced/how-to/
- https://docs.konghq.com/hub/kong-inc/request-transformer-advanced/how-to/
- https://docs.konghq.com/hub/kong-inc/request-transformer/how-to/
- https://docs.konghq.com/hub/kong-inc/request-transformer/how-to/

## Modified

- https://docs.konghq.com/gateway/3.0.x/
- https://docs.konghq.com/gateway/3.1.x/
- https://docs.konghq.com/gateway/3.2.x/
- https://docs.konghq.com/gateway/3.3.x/
- https://docs.konghq.com/hub/kong-inc/acme/
- https://docs.konghq.com/hub/kong-inc/graphql-proxy-cache-advanced/
- https://docs.konghq.com/hub/kong-inc/graphql-rate-limiting-advanced/
- https://docs.konghq.com/hub/kong-inc/grpc-gateway/
- https://docs.konghq.com/hub/kong-inc/grpc-web/
- https://docs.konghq.com/hub/kong-inc/request-transformer-advanced/
- https://docs.konghq.com/hub/kong-inc/request-transformer/


### [Resolve DOCU-2969, update request parameters](https://github.com/Kong/docs.konghq.com/pull/5827) (2023-07-19)

Resolves DOCU-2969, updating the parameter names in one of the request calls.
 
Jira: [DOCU-2969](https://konghq.atlassian.net/browse/DOCU-2969)

## Modified

- https://docs.konghq.com/konnect/api/identity-management/identity-integration

