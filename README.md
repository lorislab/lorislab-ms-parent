
# lorislab-ms-parent

This repository contains the Maven parent POM that centralizes dependency management, plugin configuration, and common build settings for LorisLab microservice modules.

[![GitHub Release](https://img.shields.io/github/v/release/lorislab/lorislab-ms-parent?color=blue)](https://github.com/lorislab/lorislab-ms-parent/releases)
[![Maven Central](https://img.shields.io/maven-central/v/org.lorislab.ms/lorislab-ms-parent?color=orange)](https://search.maven.org/artifact/org.lorislab.ms/lorislab-ms-parent)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

## How to use

In each child module that should inherit from this parent, reference it in the child's `pom.xml` under the `<parent>` element. Example:

```
<parent>
	<groupId>org.lorislab.ms</groupId>
	<artifactId>lorislab-ms-parent</artifactId>
	<version>{VERSION}</version>
</parent>
```

## Contributing

Contributions are welcome. Please open issues or pull requests against this repository. Ensure changes follow the project's coding and commit message conventions.

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.
