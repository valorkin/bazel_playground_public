1. mkdir, init (git, npm)
2. npm i -D @bazel/bazel @bazel/buildifier @bazel/ibazel
3. npm i -D @bazel/typescript
4. create .bazelrc
5. create .bazelignore with "node_modules" to make `bazel build //...` working
6. WORKSPACE & BUILD.bazel