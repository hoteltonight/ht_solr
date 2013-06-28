ht_solr
=======

This repo is for our custom solr instance

Solr Version 4.3.1

Current entensions:
- https://sourceforge.net/projects/jts-topo-suite/

### Starting Solr
```
HT_HOME=/path/to/rails/app ./htsolr
```

### Connecting to a remote Solr admin panel
```
ssh -L 127.0.0.1:8080:127.0.0.1:8983 user@hostname # visit localhost:8080 in your browser
```
