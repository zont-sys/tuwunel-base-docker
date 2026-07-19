— После того как прописали команду "sudo docker compose up certbot", закомментируйте строчку ports: - "80:80" в сервисе certbot... и перезапустите контейнеры.
Или: Сначала прописать "sudo docker compose up certbot", а потом "sudo docker compose up -d proxy element tuwunel". А потом запускать через "sudo docker compose up -d proxy element tuwunel".


— After running the "sudo docker compose up certbot" command, comment out the line ports: - "80:80" in the certbot service... and restart the containers.
Or: First run "sudo docker compose up certbot", and then "sudo docker compose up -d proxy element tuwunel". And then launch it using `sudo docker compose -d proxy element tuwunel`.
