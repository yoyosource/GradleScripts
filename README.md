# Gradle Scripts Package (GSP)

Each Script has group named as the package with 'gsp.' before it and has one task in 'gsp' for any information regarding setup.

## Using it

These scripts are written in Gradle 6.6.1. To apply any script in this repository use the line below.
```groovy
apply from: '${path}/${name}.gradle'
```
