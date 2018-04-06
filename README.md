# build-release-tag

```
composer install
```

Setup your build.properties with your origin `branch_merge_from`, `branch_merge_into` and `tag`

```
vendor/bin/phing clone composer_update merge composer_update tag push
``` 

