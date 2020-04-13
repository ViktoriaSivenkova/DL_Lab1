# DL_Lab1

В модели использована сверточная нейронная сеть, в основе принципа работы которой лежит операция свертки, применяемая к исходному изображению.

Параметры модели:

Модель обучена на 50 эпопах с batch_size = 100.
Функцией активации является ReLU. 
В качестве метрики выбрана Accuracy.
Для того, чтобы нормализовать данные использованы
Так же были использованы функция потерь CrossEntropyLoss и оптимизатор Adam с learning rate = 0.01. 
Данные били нормализованы следующим с использованием mean=(0.4914, 0.4822, 0.4465), std = (0.2023, 0.1994, 0.2010).


Результаты:

Total train epochs Accuracy =  89.38

Total test epochs Accuracy =  71.12

Total train epochs Loss =  0.003158851901185537

Total test epochs Loss =  0.01279181756991148

![Loss](https://github.com/ViktoriaSivenkova/DL_Lab1/blob/master/Loss.png)

![Accuracy](https://github.com/ViktoriaSivenkova/DL_Lab1/blob/master/Accuracy.png)
















