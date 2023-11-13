# invent

Pliki musza być umieszczone w folderze docker

Zmodyfikuj plik .env
Uzupełnij zmienne user/passwd itp.
Zmień ścieżkę do zapisywania.

Wykonaj komendy:
docker compose run inventree-server invoke update
docker compose up -d

Strona jest pod adresem:
http://localhost:1337

Do zapisu kolekcji uzyj komendy:
docker compose run inventree-server invoke export-records -f /home/inventree/data/data.json
