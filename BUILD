build_types = load("//infra/build_types.py")

build_types.declare_python_package(
    name="buildtool",
    entrypoint="buildtool.__main__:cli",
    srcs=find("**/*.*", unsafe_ignore_extension=True),
    deps=[":common"],
)
