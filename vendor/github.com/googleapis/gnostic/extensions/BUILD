load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "extension.pb.go",
        "extensions.go",
    ],
    importmap = "io_k8s_cloud_provider_gcp/vendor/github.com/googleapis/gnostic/extensions",
    importpath = "github.com/googleapis/gnostic/extensions",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/github.com/golang/protobuf/ptypes:go_default_library",
        "@io_bazel_rules_go//proto/wkt:any_go_proto",
    ],
)
