---
Author:
  - Ширяев Антон
tags:
  - VLLM
  - теория
  - задачи
date: 2024-11-10
---
# О Vision Large Language Models

`VLLM` - Vision Large Language Models.
Эти модели принимают на вход картинку и умеют отвечать по ней на вопросы на естественном языке.
Архитектурно:
* `LLM`
* некоторый `Vision encoder`
`Vision Encoder` обычно тоже архитектуры трансформер, и выдает из себя последовательность `vision-токенов`, которая кодирует информацию из картинки.
## Лекции:

* Андрей Кузнецов | Мультимодальные модели [ссылка](https://vk.com/video-210514085_456239080), [ссылка на конспект](../../../cards/Конспект%20Андрей%20Кузнецов%20Мультимодальные%20модели,%20как%20научить%20языковые%20модели%20работать%20не%20только%20с%20текстом.md).
* Елизавета Гончарова | Мультимодальные подходы [ссылка](https://vk.com/video-210514085_456239093)
* Иван Киреев | Анализ мультимодальных банковских [ссылка](https://vk.com/video-210514085_456239110)
