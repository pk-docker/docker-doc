1. docker-compose up doesn't rebuild image

   Run
   docker-compose build
   docker-compose up
   
2. Compose with env variables

   web:
     build: .
     ports:
       - "${EXTERNAL_PORT}:5000"   