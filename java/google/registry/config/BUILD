package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

java_library(
    name = "config",
    srcs = glob(["*.java"]),
    resources = glob(["files/*.yaml"]),
    deps = [
        "//java/google/registry/util",
        "@com_google_appengine_api_1_0_sdk",
        "@com_google_auto_value",
        "@com_google_code_findbugs_jsr305",
        "@com_google_dagger",
        "@com_google_flogger",
        "@com_google_flogger_system_backend",
        "@com_google_guava",
        "@javax_inject",
        "@joda_time",
        "@org_joda_money",
        "@org_yaml_snakeyaml",
    ],
)
