# k8sschedulerconfig-api

This is a maintained quasi-fork of `k8s.io/kubernetes/pkg/scheduler/apis/config`.
We want to be 1:1 API compatible bar the minimum unavoidable changes to make the package
self-sufficient.

## Motivation

if you want or need to programmatically read/write k8s scheduler configuration, and you don't
want (because, if nothing else, is actively discouraged and totally unsupported) vendor
`k8s.io/kubernetes` packages.

## Alternatives

besides avoiding existing APIs entirely and reimplement from scratch the code, none known.

## LICENSE

Apache v2, like original kubernetes
