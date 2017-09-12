## Helpful Bash Scripts

A collection of helpful Bash utility scripts so I can remember them instead of immediately forgetting & having to Google them the next time I need them. You might find them helpful too.

|What it does|C|
|---|---|
|Concatinates .json files| jq -s 'reduce .[] as $item ({}; . * $item)' *.json > ouputFile.json|
|Print just the wordcount of .txt files|wc -w *.txt|
