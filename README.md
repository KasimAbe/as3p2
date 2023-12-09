# as3p2-starter-f23

You will have to edit some of these files to get your web servers working.

The included backend server runs on port 8080, 127.0.0.1:8080

## Included material

- backend binary, hello-server
  
    `/var/www/backend/hello-server`
- frontend, index.html
  
    `/var/www/my-site/index.html`
- nginx configuration file, hello.conf

    `/etc/nginx/sites-available/hello.conf`
- service file for backend, hello-server.service

    `/etc/systemd/system/hello-server.service`
- config for setting up servers, cloud-config.yml

    `~/cloud-config.yaml`
- example curl commands for testing your server, curl.md
  
  ```bash
  curl http://143.244.211.208
  curl http://143.244.211.208/hey
  curl -X POST -H "Content-Type: application/json" \
    -d '{"message": "Hello from your server"}' \
    http://143.244.211.208/echo
  ```
