# Jfrog Artifactory README.md parsing bug
Reproduces bug https://www.jfrog.com/jira/browse/RTFACT-27126

```yaml
jfrog: 
  test: ${foo:${bar:a.b}.c}
```
