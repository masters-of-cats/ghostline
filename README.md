to use the ghostline:

1 `wget https://github.com/concourse/concourse/releases/download/v3.8.0/concourse-lite.yml`
1 `bosh create-env concourse-lite.yml`
1 `fly -t lite login -c http://192.168.100.4:8080`
1 `./reconfigure-pipeline` 


edit this repo as you need. remember that it is PUBLIC: ensure no creds are committed.
