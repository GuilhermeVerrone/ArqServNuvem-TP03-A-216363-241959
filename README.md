# TP Final - Docker Compose

Entrega: link do GitHub + PDF com prints.
E-mail: andrewsegas@unisanta.br | Assunto: TP03-TURMA-RA-RA

    docker build -t meu-nginx-custom .
    docker compose up -d
    # http://localhost:8080 (nginx custom) e http://localhost:8081 (httpd)
    docker compose logs
    docker compose ps
    docker exec -it site_custom bash
    docker compose down
