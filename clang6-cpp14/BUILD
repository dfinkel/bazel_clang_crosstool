package(default_visibility = ["//visibility:public"])

cc_toolchain_suite (
  name = "toolchain",
  toolchains = {"local|clang" : 'cc-compiler-local-clang'},
)

cc_toolchain(
  name = 'cc-compiler-local-clang',
  cpu = 'k8',
  all_files = ":empty",
  compiler_files = ":empty",
  dwp_files = ":empty",
  dynamic_runtime_libs = [":empty"],
  linker_files = ":empty",
  objcopy_files = ":empty",
  static_runtime_libs = [":empty"],
  strip_files = ":empty",
  supports_param_files = 1,
)

filegroup(
    name = "empty",
    srcs = [],
)
