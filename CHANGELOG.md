Changelog
=========

## 1.1.0 (2014-07-27)

### Feature
+ [PR](https://github.com/rstudio/redx/pull/1): Add new api endpoint, `/orphans`, that returns or deletes all frontends and backends that are orphaned.

## 1.1 (2014-07-27)

### Bug Fixes
+ [BUG](https://github.com/rstudio/redx/commit/d5051bbdc573b5017382268ec7dcf118a2fe0305): in common condition, the get_frontend function in the redis library would not close the connection or release it back to the keepalive pool. 