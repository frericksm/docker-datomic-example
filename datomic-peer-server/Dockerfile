FROM frericksm/datomic-peer-server:0.9.5544
# the hostname 'datomicdb' is created by linking a Datomic Pro Starter container with the db alias
# docker-compose does this for us, but it can be done with docker run --link
CMD ["-a", "ak,ys", "-d", "mbrainz,datomic:dev://datomicdb:4334/mbrainz-1968-1973"]