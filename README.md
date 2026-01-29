# Detekcja i zliczanie ludzi ze zdjęć

Projekt do **detekcji ludzi i zliczania ich na zdjęciach** z użyciem FastAPI, RabbitMQ i workerów w Dockerze.  

## Jak działa
1. Wysyłasz zdjęcie do API (FastAPI).  
2. Zadanie trafia do kolejki (RabbitMQ).  
3. Worker przetwarza obraz i zwraca liczbę osób.  

## Technologie
- FastAPI  
- RabbitMQ  
- 2× Worker  
- Docker / Docker Compose  

## Uruchomienie
```bash
docker-compose up --build
