# Module 8
1. How many data your publlsher program will send to the message broker in one run?
Lima pesaan, yaitu:
a. User ID: "1", Nama Pengguna: "2206828140-Amir"
b. User ID: "2", Nama Pengguna: "2206828140-Budi"
c. User ID: "3", Nama Pengguna: "2206828140-Cica"
d. User ID: "4", Nama Pengguna: "2206828140-Dira"
e. User ID: "5", Nama Pengguna: "2206828140-Emir"
2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Ini berarti bahwa program subscriber dan publisher terhubung ke server yang sama. Jadi nanti publisher akan mengirim event ke servernya, dan subscriber akan mendengar pesan-pesan masuk di server yang sama juga.

### First run of RabbitMQ
![RabbitMQ Running](src/asset/rabbitmq.png)

### Sending and Receiving Events
![Sending and receiving events](src/asset/sending-receiving.png)
Ketika publisher dijalankan, program akan mengirim 5 pesan ke broker dan nantinya akan diterima oleh subscriber.

