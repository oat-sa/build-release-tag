# build-release-tag

## Setup

```
composer install
```

## Configure

Setup your build.properties with your origin  `repository`, `branch_merge_from`, `branch_merge_into` and `tag_name`




## Run

Update/push composer.json and composer.lock on source repository then run following command to automaticaly update branch and create tag

```
vendor/bin/phing clone composer_install merge composer_install tag push
``` 

