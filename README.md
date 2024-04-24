# Nama: Clara Sista Widhiastuti
# NPM: 2206825782
# Kelas: ADPRO-A

a. How many data your publlsher program will send to the message broker in one
run? </br>
Dalam satu kali run `main` maka akan memanggil 5 kali `publish_event`. Maka akan mengirim 5 data ke _message broker_

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean? </br> 
Jika url subscriber dan publisher sama artinya keduanya terhubung pada message broker AMPQ yang berjalan di machine yang sama. Keduanya berinteraksi pada broker instance yang sama sehingga memungkinkan publisher mengirimkan pesan dan subcriber menerima pesan tersebut. 

## RabbitMQ
![](https://imgur.com/a/3zEu2jr)

## After `cargo run`
Setelah dijalankan cargo eun sistem mengirimkan 5 data ke message broker 
![](https://imgur.com/4RuDlgH)
![](https://imgur.com/TK4fCqx)