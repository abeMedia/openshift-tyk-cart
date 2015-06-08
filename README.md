Install using `rhc app-create APP_NAME http://cartreflect-claytondev.rhcloud.com/reflect?github=abemedia/openshift-tyk-cart mongodb-2.4 http://cartreflect-claytondev.rhcloud.com/reflect?github=smarterclayton/openshift-redis-cart`

or `rhc app create APP_NAME http://cartreflect-claytondev.rhcloud.com/reflect?github=abemedia/openshift-tyk-cart \  
  --env TYK_SECRET=foo \
  --env TYK_REDIS_HOST=foo \
  --env TYK_REDIS_PORT=foo \
  --env TYK_REDIS_PASSWORD=foo \  
  --env TYK_MONGODB_URL=bar`
  