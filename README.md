# criação de senha 
````docker run --rm -it -v "$PWD/mosquitto/config:/mosquitto/config" eclipse-mosquitto:2 mosquitto_passwd -c -b /mosquitto/config/passwd aluno aluno123````