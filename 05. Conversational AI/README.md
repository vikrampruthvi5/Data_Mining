# Natural Language Processing

## Setting up environment
* Clone repository
* create a file named `app.api_json.json` under Data_Mining/05.Conversational \AI/ folder
* add your google api key in json format
```
[
  {
    "kgsearch": "<YOUR API KEY HERE>"
  }
]
```

## Gist
* Identify user input
* Retrieve information
  * Identify Tokens
  * Identify POS Tags
* Deal with Semantic and Syntactic problems
  * semantic problems : Use google knowledge graph
  
## Python Packages used
* nltk
* json
* urllib
* gtts
