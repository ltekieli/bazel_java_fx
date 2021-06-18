java_binary(
    name = "HelloFx",
    srcs = glob(["*.java"]),
    deps = ["@openjfx//:openjfx"],
    jvm_flags = [
        "--module-path=external/openjfx/javafx-sdk-16/lib/",
        "--add-modules=javafx.controls",
    ],
    main_class = "lt.gui.HelloFx",
    data = ["@openjfx//:openjfx"],
)

