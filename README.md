# bazel-py-setup
This is a sample Python project where Bazel is being used as the build tool. One can use this project to customize and use it as per his requirements.

Workspace: A workspace is a directory on your filesystem that contains the source files for the software you want to build, as well as symbolic links to directories that contain the build outputs. Each workspace directory has a text file named WORKSPACE which may be empty, or may contain references to external dependencies required to build the outputs

Run the command to build
```
cd package_1
bazel build hello
```

This command will produce the output
```
bazel-bin/package_1/hello
```