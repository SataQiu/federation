load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "client_ca_hook.go",
        "client_util.go",
        "controller.go",
        "doc.go",
        "import_known_versions.go",
        "master.go",
        "services.go",
    ],
    importpath = "k8s.io/kubernetes/pkg/master",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/glog:go_default_library",
        "//vendor/github.com/prometheus/client_golang/prometheus:go_default_library",
        "//vendor/k8s.io/api/admissionregistration/v1beta1:go_default_library",
        "//vendor/k8s.io/api/apps/v1:go_default_library",
        "//vendor/k8s.io/api/apps/v1beta1:go_default_library",
        "//vendor/k8s.io/api/apps/v1beta2:go_default_library",
        "//vendor/k8s.io/api/authentication/v1:go_default_library",
        "//vendor/k8s.io/api/authentication/v1beta1:go_default_library",
        "//vendor/k8s.io/api/authorization/v1:go_default_library",
        "//vendor/k8s.io/api/authorization/v1beta1:go_default_library",
        "//vendor/k8s.io/api/autoscaling/v1:go_default_library",
        "//vendor/k8s.io/api/autoscaling/v2beta1:go_default_library",
        "//vendor/k8s.io/api/batch/v1:go_default_library",
        "//vendor/k8s.io/api/batch/v1beta1:go_default_library",
        "//vendor/k8s.io/api/certificates/v1beta1:go_default_library",
        "//vendor/k8s.io/api/core/v1:go_default_library",
        "//vendor/k8s.io/api/events/v1beta1:go_default_library",
        "//vendor/k8s.io/api/extensions/v1beta1:go_default_library",
        "//vendor/k8s.io/api/networking/v1:go_default_library",
        "//vendor/k8s.io/api/policy/v1beta1:go_default_library",
        "//vendor/k8s.io/api/rbac/v1:go_default_library",
        "//vendor/k8s.io/api/rbac/v1beta1:go_default_library",
        "//vendor/k8s.io/api/storage/v1:go_default_library",
        "//vendor/k8s.io/api/storage/v1beta1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/intstr:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/net:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/discovery:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/registry/generic:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/server:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/server/healthz:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/server/storage:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/storage/storagebackend/factory:go_default_library",
        "//vendor/k8s.io/client-go/informers:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/core/v1:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/api/legacyscheme:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/admission/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/admissionregistration/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/apps/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/authentication/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/authorization/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/autoscaling/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/batch/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/certificates/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/componentconfig/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/core:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/core/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/events/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/extensions/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/imagepolicy/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/networking/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/policy/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/rbac/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/scheduling/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/settings/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/apis/storage/install:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/client/clientset_generated/internalclientset/typed/core/internalversion:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/kubeapiserver/options:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/kubelet/client:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/master/reconcilers:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/master/tunneler:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/admissionregistration/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/apps/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/authentication/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/authorization/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/autoscaling/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/batch/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/certificates/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/endpoint:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/endpoint/storage:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/rangeallocation:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/service/ipallocator:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/service/ipallocator/controller:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/core/service/portallocator/controller:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/events/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/extensions/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/networking/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/policy/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/rbac/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/scheduling/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/settings/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/registry/storage/rest:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/routes:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/util/async:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/util/node:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//vendor/k8s.io/kubernetes/pkg/master/ports:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/master/reconcilers:all-srcs",
        "//vendor/k8s.io/kubernetes/pkg/master/tunneler:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
