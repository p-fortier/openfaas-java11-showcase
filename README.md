# openfaas-java11-showcase
https://github.com/openfaas/templates/issues/255#issuecomment-813910704

__command list__:
- `faas template store pull java11-vert-x`
- `faas new --lang java11-vert-x read-body`
- `faas build -f read-body.yml`
- `faas push -f read-body.yml`
- `faas deploy -f read-body.yml`
