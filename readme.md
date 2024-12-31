A very simple tool to reformat json string in a text view. Support both command line and universe actions!

-------
Before Start

Please install jq via brew

```
brew install jq
```

-------

Examples:

jq .["resume"] {"resume":{"name":"yingwei"},"date":"20241231"}

jq .["date"] {"resume":{"name":"yingwei"},"date":"20241231"}

jq  {"resume":{"name":"yingwei"},"date":"20241231"}

jq 20241231

-------
Thanks to the incredible project jq, get more infomation from their web site. https://jqlang.github.io/jq/