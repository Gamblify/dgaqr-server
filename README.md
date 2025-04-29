A sample command-line application providing basic argument parsing with an entrypoint in `bin/`.

Run the code using `dart run bin/dgaqr_server.dart`

Test key and certificate generated using `openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -sha256 -days 3650 -nodes -subj "/C=DK/ST=Test/L=Copenhagen/O=Gamblify/OU=Dev/CN=localhost"` 