load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "const.go",
        "edwards25519.go",
    ],
    importmap = "io_k8s_cloud_provider_gcp/vendor/golang.org/x/crypto/ed25519/internal/edwards25519",
    importpath = "golang.org/x/crypto/ed25519/internal/edwards25519",
    visibility = ["//vendor/golang.org/x/crypto/ed25519:__subpackages__"],
)
