eStoreMedia Recruitment Data IT

Skrypt uruchamia się w konterze Dockera, aby go zbudować należy w folderze "docker" wpisać następującą komendę
```sh
docker-compose up
```
Aplikacja będzie dostępna w przeglądarce pod adresem http://localhost:8000/.
Oba zadania wykonują się w tym samym skrypcie 'index.php' który po uruchomieniu najpierw pobiera html i zapisuje go do csv a następnie na podstawie zapisanego csv generuje tabelę.
Aby zmienić tryb pracy skryptu z pobierania html na dysk na przetwarzanie html w locie należy zmienić wartość parametru "download" w index.php na "false".

Dane techniczne:
- PHP8
