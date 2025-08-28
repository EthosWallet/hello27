workspace(name = "test_root_workspace")

# DC vulnerability - this package doesn't exist in Bazel Central Registry
bazel_dep(name = "nonexistent_test_package", version = "1.0.0")

# Reference to second workspace (subfolder1)
local_repository(
    name = "subfolder1_workspace",
    path = "./subfolder1"
)
