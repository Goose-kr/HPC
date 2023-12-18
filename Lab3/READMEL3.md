Tower original
![Tower.bmp](Tower.bmp)
Tower CPU:  579.9344708919525
![Tower1.bmp](Tower1.bmp)
Tower GPU:  0.49516797065734863 
![Tower2.bmp](Tower2.bmp)

Priroda original
![priroda.bmp](priroda.bmp)
Priroda CPU:  438.9732880592346
![priroda1.bmp](priroda1.bmp)
Priroda GPU:  0.4137566089630127
![priroda2.bmp](priroda2.bmp)

Road original
![Road.bmp](Road.bmp)
Road CPU:  222.42010879516602
![Road1.bmp](Road1.bmp)
Road GPU:  0.2813892364501953
![Road2.bmp](Road2.bmp)


Так как в данном примере были использованы примеры больших изображений, то во всех примерах обработка на GPU занимала на порядок меньше времени. Однако если бы изображение было бы не большое, то результат мог бы быть обратным.
Данный факт обусловлен тем, что процессор имеет меньше количество ядер, но более производительных и операции выполняются последовательно. А на GPU много ядер, которые слабее, но используют параллельное вычисление.
