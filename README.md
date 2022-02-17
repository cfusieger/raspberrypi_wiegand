## Raspberry Pi Wiegand Reader

### Descripción
Codigo para  leitura de tags/tarjetas RFID mediante una leitora de RFID conectada a uma Raspberry Pi com Pigpio.

### Requisitos 
* Python 2.7
* [Pigpio](http://abyz.me.uk/rpi/pigpio/download.html)

### Instalacão do Pigpio e dependecias
    $ sudo apt-get update
    $ sudo apt-get install pigpio python-pigpio python3-pigpio git -y


### Instalacão

    $ sudo pigpiod
    $ git clone https://github.com/alxsmora1/rasberrypi_wiegand.git
    $ cd raspberrypi_wiegand
    $ python wiegand.py


### Metodo de uso
* GPIO (BCM)
* Se necesita conectar o cablo verde (D0) no GPIO 14 eo cablo blanco (D1) no GPIO 15.
* Também e nessessario conectar cabo terra (GND) da leitora em um pino GND da placa Raspberry, pois pode geraralgum ruido durante a leitura dos dados (ruido que pode gerar leitura incorreta dos dados).   
