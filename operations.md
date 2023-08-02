## Operations

The following table shows the main request that can be performed over a Registry

|Operation|Request|
|---------|--------|
|List repositories|curl -kX GET https://<REGISTRY_URL>:<REGISTRY_PORT>/v2/_catalog|
|List all tags of a repository|curl -kX GET https://<REGISTRY_URL>:<REGISTRY_PORT>/v2/<REPOSITORY>/tags/list|
