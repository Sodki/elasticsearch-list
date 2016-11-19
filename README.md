# Elasticsearch List #

An Elasticsearch plugin that lists installed plugins.

## Installation ##

To install this plugin just use the `plugin` command from Elasticsearch itself. The location of the `plugin` command may vary, depending on how you installed Elasticsearch. 

### Elasticsearch 2.x ###

```
bin/plugin install notonthehighstreet/elasticsearch-list/2.0
```

### Elasticsearch 1.x ###

```
bin/plugin --install notonthehighstreet/elasticsearch-list/1.0
```

## Usage ##

After installation, open it on the browser. If installed locally, the default URL would be `http://localhost:9200/_plugin/list`.
