# golos-links
Collection of links to the public resources in machine-readable format. The entry point for any kind of 3rd party software.

# example react
```
        const fetchData = async () => {
            fetch("https://raw.githubusercontent.com/golos-blockchain/golos-links/main/api-nodes.json")
            .then(result => result.json())
            .then(result => setNodes(result), error => console.log("unable to load nodes from hithub"));
        }
```

