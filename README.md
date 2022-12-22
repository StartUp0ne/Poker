# Pocer

## Основное задание
Реализованя функция best_hand, которая принимает на вход покерную "руку" (hand) из 7ми карт и
возвращает лучшую (относительно значения, возвращаемого hand_rank) "руку" из 5ти карт. 

У каждой карты есть масть(suit) и ранг(rank)

Масти: трефы (clubs, C), пики (spades, S), червы (hearts, H), бубны (diamonds, D)

Ранги: 2, 3, 4, 5, 6, 7, 8, 9, 10 (ten, T), валет (jack, J), дама (queen, Q), король (king, K), туз (ace, A)

Пример работы:

Входные данные: "6C 7C 8C 9C TC 5C JS"

![image](https://user-images.githubusercontent.com/108416225/209170362-542f16ec-ea1d-47b2-874b-8cc1453a7811.png)

Результат: ('6C', '7C', '8C', '9C', 'TC')

![image](https://user-images.githubusercontent.com/108416225/209170712-7dbe07b3-864a-4fa4-b920-d09b4a510eed.png)

## Дополнительное задание:

Реализована функция best_wild_hand, которая принимает на вход покерную "руку" (hand) из 7ми
карт и возвращает лучшую (относительно значения, возвращаемого hand_rank) "руку" из 5ти карт.
Кроме прочего в данном варианте "рука" может включать джокера. 

Джокеры могут заменить карту любой масти и ранга того же цвета, в колоде два джокера. 
Черный джокер '?B' может быт использован в качестве треф или пик любого ранга, 
красный джокер '?R' - в качестве черв и бубен любого ранга.

Пример работы:

Входные данные: "TD TC 5H 5C 7C ?R ?B"

![image](https://user-images.githubusercontent.com/108416225/209171562-e7059646-e8a5-4264-8f01-815fc274cc28.png)

Результат: ('TD', 'TC', '7C', 'TH', 'TS')

![image](https://user-images.githubusercontent.com/108416225/209171687-ba170718-a023-4d05-99a2-4889127bc411.png)

## Прохождение тестов

Тесты:

![image](https://user-images.githubusercontent.com/108416225/209172016-4aa9699e-3bd8-4541-8b02-bb26274cf4be.png)

Результаты:

![image](https://user-images.githubusercontent.com/108416225/209172158-710f70bd-3ac9-4b40-945a-ea0449e3aeba.png)

