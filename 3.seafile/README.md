# Seafile

```bash
vault kv put kv/seafile INIT_SEAFILE_ADMIN_EMAIL=admin@seafile.com
vault kv patch kv/seafile INIT_SEAFILE_ADMIN_PASSWORD=admin_password
vault kv patch kv/seafile REDIS_PASSWORD=your-redis-password-here
vault kv patch kv/seafile JWT_PRIVATE_KEY=A3s85fwpaq2iipd5gY7TvwholJ23BedJDvfjfReu
vault kv patch kv/seafile SEAFILE_MYSQL_DB_PASSWORD=db_dev
vault kv patch kv/seafile INIT_SEAFILE_MYSQL_ROOT_PASSWORD=db_dev
vault kv patch kv/seafile OAUTH_CLIENT_ID=kyuPSaHIc2DAoBHxqQck78dyJzdi28KBDZsHCu3i
vault kv patch kv/seafile OAUTH_CLIENT_SECRET=LkrXmwZkFZgIGp4wdIHWkGY31Hs6laSvpPbSOPvMfZsxqhAAN3FkRRpt9ucHBRo63FFX4eLaDsn4JGolrq77LVI83QBr9Wk8ST44CUmeplU7AMkcM1DumkshFJIQyyhW
vault kv patch kv/seafile ONLYOFFICE_JWT_SECRET=XG4FcDp9Rvj8K2QwS5tZv6YbAa3uH1NmJ7eLkP0qOxIiUyVlWoEh
```



# Checklist

- [X] Enable [seadoc](https://manual.seafile.com/11.0/extra_setup/setup_seadoc/) so the Wiki feature will work
- [X] fix self signed TLS 
- [X] Add onlyoffice 
- [X] Update config to Seafile 13

## Sources
* [Installation of Seafile Server Community Edition with Docker](https://manual.seafile.com/13.0/setup/setup_ce_by_docker/#getting-started)
* [Setup Seafile with a single K8S pod with K8S resources files](https://manual.seafile.com/12.0/setup/k8s_single_node/#system-requirements)
* [Environment Variables](https://manual.seafile.com/12.0/config/env/)
* [Dockerhub](https://hub.docker.com/r/seafileltd/seafile-mc/tags)
* [Seafile AI extension](https://manual.seafile.com/13.0/extension/seafile-ai/#deploy-seafile-ai-basic-service)

Old source should probably be ignored
* [Setup Seafile 11](https://manual.seafile.com/11.0/deploy/deploy_with_k8s/)
