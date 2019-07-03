
# sopsencodedsecrets

A standalone repo with a single kustomize plugin.

Loads secrets from a [sops](https://github.com/mozilla/sops)-encoded file.

Based on https://github.com/Agilicus/kustomize-sops and
the [SecretsFromDatabase](https://github.com/kubernetes-sigs/kustomize/blob/master/plugin/someteam.example.com/v1/secretsfromdatabase/SecretsFromDatabase.go) example plugin.

To do a standalone test:

```
git clone git@github.com:monopole/sopsencodedsecrets.git
cd sopsencodedsecrets
go test SopsEncodedSecrets_test.go
```

To see it work as a plugin, see this [example](https://github.com/kubernetes-sigs/kustomize/blob/master/docs/plugins/goPluginGuidedExample.md).


