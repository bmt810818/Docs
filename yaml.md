# Comparison Yaml with other serialization formats

## 1. Comparison with JSON
- Due to the conciseness, JSON serialization and deserialization is much faster than YAML

## 2. Comparison with TOML
## 3. Comparison with XML

*YAML has been criticized for its significant whitespace, confusing features, insecure defaults, and its complex and ambiguous specification*
Because:
```
- Configuration files can execute commands or load contents without the users realizing it.
- Editing large YAML files is difficult, as indentation errors can go unnoticed.
- Type autodetection is a source of errors. For example, unquoted Yes and No are converted to booleans; software version numbers might be converted to floats.
- Truncated files are often interpreted as valid YAML due to the absence of terminators.
- The complexity of the standard led to inconsistent implementations and making the language non-portable.
```
*The perceived flaws and complexity of YAML has led to the emergence of stricter alternatives such as StrictYAML and NestedText.*
