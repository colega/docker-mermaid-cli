# docker-mermaid-cli
Docker image for the Mermaid CLI utility. Useful for generating diagrams written in Mermaid JS.

## Sample usage:
```sh
docker run -v $PWD:/data colega/mermaid-cli --cssFile /data/mermaid.css -i /data/diagram.mmd
```
