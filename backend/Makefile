build:
	docker build . -t backend

run: 
	docker build . -t backend
	docker run --rm --env-file .env --name api -p 8000:8000 backend