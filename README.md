Simple repo with a simple nginx docker compose file.

This will allow you to deploy nginx through docker compose and copy the nginx.conf file from the repo directory.
Additionally, it will onboard a /src/docker/nginx/sites-enabled directory to the container's /sites-enabled directory which
will allow for a traditional configuration instead of cramming everything in the nginx.conf file.
