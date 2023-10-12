# ArangoDB
ArangoDB Deployment
# Arango Restor 
arangorestore \
  --server.endpoint tcp://Localhost:8529 \
  --server.username username \
  --server.password password \
  --server.database DBname \
  --create-database true \
  --input-directory "dir_name"
