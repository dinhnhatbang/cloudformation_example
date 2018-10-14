# Cloudformation example




* Convert JSON to YML

```
 ruby -ryaml -rjson -e 'puts YAML.dump(JSON.load(ARGF))' < wordpress.template > wordpress.yml
```


* Convert YML to JSON

Install package: https://github.com/bronze1man/yaml2json

```
yaml2json < wordpress.yml > wordpress.json
```
