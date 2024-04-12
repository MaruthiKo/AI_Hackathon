### CURL to make a post request

> Note: Replace space character with `%20`

```shell
curl -X 'POST' \
  'http://0.0.0.0:8000/embed_text?text=geta%20table%20with%20a%20lamp' \
  -H 'accept: application/json' \
  -d ''
```