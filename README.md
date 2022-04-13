eStoreMedia Recruitment Data IT

Skrypt można uruchomić w kontenerze, aby go zbudować należy w folderze "docker" wpisać następującą komendę
```sh
docker-compose up
```
Aplikacja będzie dostępna w przeglądarce pod adresem http://localhost:8000/.
Oba zadania wykonują się w tym samym skrypcie 'index.php', który po uruchomieniu najpierw pobiera html i zapisuje go do csv, a następnie wyświetla tabelę.
Aby zmienić tryb pracy skryptu z pobierania html na dysk na przetwarzanie html w locie należy zmienić wartość parametru "download" w index.php na "false".

Wykorzystane technologie:
- PHP8
- Composer
