# ArangoDB
ArangoDB Deployment
# Arango Restor 
arangorestore \ 
--server.endpoint tcp://host:8529 \ 
--server.username username \ 
--server.password password \ 
--all-databases true \ 
--server.database DBname \ 
--create-database true \ 
--input-directory "dir_name"
# Arango Dump
arangodump \
--output-directory "dir_name" \
--server.username username \
--overwrite true \
--all-databases true \
--server.endpoint tcp://host:8529 \
--server.password password


