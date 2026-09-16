Start services `docker-compose --env-file config.env up -d --build`

Go to `localhost:9001`

Get MINIO Acces Key and save into `config.env/MINIO_ACCESS_KEY`

Stop services `docker-compose down`

Start again `docker-compose --env-file config.env up -d --build`

--------------------------------------------------

`docker-compose -f --env-file config.env up -d --build`



Para levantar ngrok y que funcione con docker
`ngrok http 5002 --host-header="localhost:5002"`