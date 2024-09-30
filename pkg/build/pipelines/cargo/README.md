<!-- start:pipeline-reference-gen -->
# Pipeline Reference


- [cargo/build](#cargobuild)

## cargo/build

Compile an auditable rust binary with Cargo

### Inputs

| Name | Required | Description | Default |
| ---- | -------- | ----------- | ------- |
| install-dir | false | Directory where binaries will be installed  | bin |
| modroot | false | Top directory of the rust package, this is where the target package lives. Before building, the cargo pipeline wil cd into this directory. Defaults to current working directory  | . |
| opts | false | Options to pass to cargo build. Defaults to release  | --release |
| output | false | Filename to use when writing the binary. The final install location inside the apk will be in prefix / install-dir / output  |  |
| prefix | false | Installation prefix. Defaults to usr  | usr |


<!-- end:pipeline-reference-gen -->