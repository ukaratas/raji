# Rajiformes

A simple State Machine Business Process Engine  

## Searching an items in specified process

1. GET  /metadata/view/search
   >Get search form metadata to generate
2. GET /data/search
   >Call search entity for filtered items

## Displaying an item

1. GET /metadata/view/display
   >Get display form metadata to generate
2. GET /data/search
   >Call search entity for specified item  

## Creating new item

1. GET  /metadata/data/new
   >Get initializer informations for specific process
2. POST /data/new
   >Start a specific process instance with initializer fields
3. GET /metadata/view/modify
   >Get modify form metadata to generate
4. POST /data/modify
   >Post form data to save