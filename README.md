# PCB-MultiRobot-WAKANDA-V1-

![image](https://github.com/BoverGroup/PCB-MultiRobot-WAKANDA-V1-/assets/144978109/c677837a-8cf3-4f74-9401-6dc6763fcf90)

![image](https://github.com/BoverGroup/PCB-MultiRobot-WAKANDA-V1-/assets/144978109/034e5689-9435-410f-bdcd-a6544123a888)
![image](https://github.com/BoverGroup/PCB-MultiRobot-WAKANDA-V1-/assets/144978109/e5eabdf8-448d-43cc-a0cb-d837a147eff8)

## Descripción

El PCB Wakanda está diseñado especialmente para competencias de Sumo o MiniSumo. Su principal ventaja radica en la separación de la alimentación general de la de los motores, lo que permite que este dispositivo pueda ser alimentado por un voltaje de hasta 50V, mientras que el microcontrolador y periféricos serán alimentados por separado a través de una entrada de 5V (mediante alguna fuente step-down o regulador externo).

Wakanda cuenta con numerosas salidas para periféricos, como por ejemplo sensores Sharp o QR1113 e incluso cuenta con una salida I2C para conectar dispositivos como pantallas OLED o sensores de posición como la MPU6050. Esta capacidad le otorga una ventaja considerable frente a otras placas del mercado, al permitir la inclusión de varios sensores, botones e incluso LEDs indicadores para facilitar el uso y aumentar el rendimiento de tu robot.

En cuanto a los Controladores de Motores, pueden soportar una corriente de 4A de trabajo y hasta 30V, los cuales son alimentados directamente a través de la bornera de VCC y pueden soportar hasta 30V. Con ellos, se puede controlar la velocidad y la dirección de giro de ambos motores del robot.

Este PCB incluye un microcontrolador ESP32 que incorpora wifi y bluetooh para incluir en el proyecto, tambien es compatible con la IDE de Arduino, lo cual le otorga cierta facilidad al usuario familiarizado con esta plataforma, e incluso a alguien nuevo que se está adentrando en el mundo de la robótica y la programación.

Actualmente es utilizado en nuestro robot Sumo que compite en la LIGA NACIONAL DE ROBOTICA ARGENTINA y cuenta con 5 sensores Sharps, 2 pulsadores , una Oled por I2C y para alimentar lo alimentamos con una bateria lipo de 6S y una step down que baja la tension a 5v para alimentar el uC y sus perifericos
![image](https://github.com/BoverGroup/PCB-MultiRobot-WAKANDA-V1-/assets/144978109/eba73c04-7e44-448d-b974-02a878d2ca09)
