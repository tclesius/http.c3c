## Goals
- [x] Response Body json method / lambda 
- [~] Headers implementieren
- [~] Cookies implementieren
- [~] Request body hinzufuegen (verschiedene encodings)
- [~] Transfer Encoding Chunked empfangen unterstuetzen
- [ ] Transfer Encoding Chunked senden unterstuetzen
- [ ] POST urlencoded data
- [ ] Requests über http proxies implementieren
- [ ] Redirects unterstützen (allow_redirects) / History -> List(Response) aufbauen
- [ ] Socket Timeout einbauen
- [ ] Tests schreiben
- [ ] Sessions implementieren siehe: https://docs.python-requests.org/en/latest/user/advanced/
- [ ] Requests einzeln bauen und diese dann senden vielleicht einbauen
 
## Goals Advanced
- [ ] Websockets implementieren
- [ ] Transfer Encoding gzip empfangen unterstuetzen
- [ ] Transfer Encoding gzip senden unterstuetzen


## Quick wins
- [x] curl -v jsonip.com debug messages
- [x] User-Agent: c3c/http in request header hinzufuegen
- [z] Rename Status code and Status message 