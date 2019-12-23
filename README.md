# `elasticsearch.base` - ContEco

Official Elasticsearch base image with minor configuration change.  
See `conteco.docs.overview` for more information on the ContEco ecosystem.

## Configuration

The following configuration change was made in `jvm.options`:
```bash
# default memory allocation reduced to 512m
-Xms512m
-Xmx512m
```

## Tags

* 7.1.1
