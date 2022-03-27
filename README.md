# ГЕНЕРАЦИЯ ТРЁХМЕРНОГО ФРАКТАЛА МАНДЕЛЬБАЛБ С ПОСЛОЙНОЙ ВИЗУАЛИЗАЦИЕЙ

**Язык:** С++


**Использованные библиотеки:** SDL


**Сборка:** запустите Makefile:

make

./bulber


**Краткое описание:** 

На примере 3D множества Мандельброта пользователь в режиме реального времени может исследовать слои фрактала.


**Клавиши управления:** 

Стрелки вверх/вниз/влево/вправо—перемещение фрактала на плоскости в соответствующем направлении

Pg Up / Pg Dn —  увеличение и уменьшение масштаба

A(S,D,F) / Z(X,C,V) — перемещение плоскости вдоль фрактала в выбранном направлении на соответствующую толщину (0.01, 0.001, 0.0001, 0.00001)

R — возвращение в исходное положение

T — сохранения текущего изображения слоя

G(H,J) / B(N,M) — сохранение N изображений слоев (10, 50, 100 соответственно), следующих за текущим слоем, в выбранном направлении и возвращение в исходное положение
