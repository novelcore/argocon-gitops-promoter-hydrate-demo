
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/novelcore/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 5ba257eeaeacc818ca63d8a8673aeb903756437b
kustomize build ./user-configuration/development
```