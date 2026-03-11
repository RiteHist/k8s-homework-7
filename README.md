# k8s-homework-7

## Задание 1

Ссылка на [helm чарт](https://github.com/RiteHist/k8s-homework-7/blob/main/SimpleHelmChart)

В качестве приложения использовались файлы из ДЗ для запуска nginx через ingress с https.

## Задание 2

Запуск приложения в пространстве имен app1:

![alt text](https://github.com/RiteHist/k8s-homework-7/blob/main/media/1.PNG?raw=true)

Попытка запуска приложения в том же пространстве имен:

![alt text](https://github.com/RiteHist/k8s-homework-7/blob/main/media/2.PNG?raw=true)

Запуск приложения в пространстве имен app2:

![alt text](https://github.com/RiteHist/k8s-homework-7/blob/main/media/3.PNG?raw=true)

Проверка, что nginx работает через port-forward к сервису:

![alt text](https://github.com/RiteHist/k8s-homework-7/blob/main/media/4.PNG?raw=true)

Проверка, что ingress работает:

![alt text](https://github.com/RiteHist/k8s-homework-7/blob/main/media/5.PNG?raw=true)
