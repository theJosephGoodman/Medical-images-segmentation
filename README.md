# Medical-images-segmentation

В данном ноутбуке я выполнял домашнее задание курса DeepLearningSchool - сегментация меланомы на снимках.
Провёл сравнение качество и скорость работы различных архитектур и функций потерь.

**Реализовал следующие архитектуры:**

*Segnet, Unet(c nearest-neighbour upsample в декодер части) и Unet(с convtranspose в декодер части)*


**Ключевая метрика**:
*IoU(Jaccard index)*

**Использовал лоссы:**
*Dice loss, BCE loss*


**Трудности во время выполнения:**
*Во время выполнения работы столкнулся с проблемой переполнения памяти GPU после обучения какой-либо сети. Память забивалась уже использованными данными и не очищалась стандартным garbage collector. Проблема была решена только после определенных команд в определенной последовательности, указанных в ноутбуке после обучения каждой сети*
