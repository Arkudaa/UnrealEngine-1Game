# UnrealEngine-1Game
Teacher's project for refference.

Описание.
3 Level-а. 
Level 1 Паркур из геметрических обьектов с различными материалами, префабы светильника, pointlight для подсветки блоков,вращающиеся блоки, которые нужно собрать . Цель дойти до телепорта (Goal). Для более быстрого тестирования  я убрал сейчас ResetBox (должен будет покрывать пол и при касании героем срабатывает Ragdoll функция, позже заменим на функцию restart). При касании GOAL  перекидывает на Level2
Level2 Паркур на Landscape. Cмоделированный Landscape, дизайн  в т.ч при помощи мода Foliage. Цель дойти до телепорта (Goal). Должны быть элементы: Разбивающиеся на части блоки, движущиеся платформы и движущиеся  hazard блоки (уменьшают здоровье героя)- анимация сделана при помощи Cinematics, healpack (увеличивает здоровье героя), вращающиеся блоки, которые необходимо собирать. Пол покрывает resetBox (для быстрого тестирования сейчас убран со сцены), при касании срабатывает фуункция ragdoll ( позже restart). 
При Health <0 срабатывает функция Ragdoll. Телепорт  перекидывает на Level3
Level 3 - Паркур в замке. Ночное небо,  начали строить замок из ассетов Infinity Blade grass Land. Texture tiling (при помощи Texture coordinates) для тайлинга  материалов для замка 

На каждом уровне- работающий HUD- Score (считает собранные вращающиеся блоки ) и Health ( progress bar- здоровье уменьшается/ увеличивается)





