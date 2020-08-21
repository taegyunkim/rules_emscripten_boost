# rules_emscripten_boost

Bazel build rules for emscripten-ports/boost (headers only), doesn't have all the rules.

```
git_repository(
    name = "com_github_taegyunkim_rules_emscripten_boost",
    commit = "3b9dd84879ede431c4233b137a5345490e060f58",
    shallow_since = "1598019040 -0400",
    remote = "https://github.com/taegyunkim/rules_emscripten_boost"
)

load("@com_github_taegyunkim_rules_emscripten_boost//boost:boost.bzl","boost_deps")

boost_deps()
```

# Acknowledgements

- [rules_boost](https://github.com/nelhage/rules_boost)
