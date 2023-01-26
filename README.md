# Домашнее задание к занятию "`10.5 «Балансировка нагрузки `" - `Mashalov V.V.`
### Задание 1
```
Что такое балансировка нагрузки и зачем она нужна?

Приведите ответ в свободной форме.
```

> Балансировщик нагрузки — это сервис, который занимается распределением нагрузки между приложениями, которые находятся за ним, стараясь максимизировать скорость и утилизировать ресурсы приложений.  
Также, гарантирует, что приложения не будут перегружены.
>> Преимущества балансировки нагрузки:
>> + сокращение времени простоя;
>> + масштабируемость; 
>> + отказоустойчивость.
---
### Задание 2
```
Чем отличаются алгоритмы балансировки Round Robin и Weighted Round Robin? В каких случаях каждый из них лучше применять?

Приведите ответ в свободной форме.
```

> В Round Robin запросы отправляются на пул серверов последовательно , как будто наши сервера одинаковой мощности.  
> В Weighted Round Robin уже идет распределение запросов согласно мощности каждого сервера из пула.
>> :saluting_face: Соответственно если у нас пул состоит из одинаковых серверов по мощности, то хорошо подойдет Round Robin, если разные мощности, то Weighted Round Robin.

