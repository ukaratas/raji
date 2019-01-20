# Rajiformes

A simple State Machine Business Process Engine  

## Message Call Order for New Instance

1. GET  /metadata/data/new
   >Get initializer informations for specific process
2. POST /data/new
   >Start a specific process instance with initializer fields
3. GET /metadata/view/modify
   >Get modify form metadata to generate
4. POST /data/modify
   >Post form data to save 