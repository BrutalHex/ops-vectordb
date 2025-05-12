# Introduction
The ops-vectordb project is a simple vector database..
It uses Qdrant helm chart to deploy a vector database.
The chart repository address is [`https://brutalhex.github.io/ops-vectordb/`](https://brutalhex.github.io/ops-vectordb/).

To release a new version of the website:  
- Modify the contents of the `ops-vectordb/myapp/templates` folder  
- Increase the chart version  
- Push the code  
- Execute [Publish Helm Chart](https://github.com/BrutalHex/ops-vectordb/actions/workflows/release.yaml) in GitHub Actions.

For more details, refer to the [ops-infra](https://github.com/BrutalHex/ops-infra) repository.  

This project creates a basic Helm repository using GitHub Pages.
