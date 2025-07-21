## 

```
kubebuilder init --domain bizaikube.io --repo github.com/madmmas/kubebackup-manager
```

```
kubebuilder create api --group backup --version v1alpha1 --kind NamespaceBackupSchedule
```

```
kubebuilder create api --group backup --version v1alpha1 --kind BackupRun
```