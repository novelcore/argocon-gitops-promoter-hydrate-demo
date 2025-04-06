
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/novelcore/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout f0c1d8d4d646fbf59edd4daad5445d524c089921
kustomize build ./user-configuration/development
```