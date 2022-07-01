# Diplom
Квантовый отжиг - специализированный алгоритм квантовой
оптимизации, для которого уже разработаны NISQ(Noisy
Intermediate-Scale Quantum) процессоры, в частности произведенные
компанией D-Wave Systems. Опыт, полученный в ходе их использования
для задач в науке и промышленности, показал, что в процессе их
работы происходит множество интересных физических эффектов. Их
исследование затруднено тем, что NISQ процессоры уже слишком
сложны для их моделирования.

В данной работе был проведен подобный анализ. Для обхода
ограничений, вызванных проклятием размерности, были использованы
тензорные сети. Изначально метод был разработан для исследований в
области физики конденсированного состояния, что не мешает
применять его для исследования NISQ процессоров.

На примере задачи о поиске основного состояния модели Изинга был
проведен сравнительный анализ решений, полученных на квантовом
компьютере и тензорными сетями. Используя подход тензорных сетей
было показано, что основной источник ошибок связан со свойствами
исследуемой цепочки Изинга, а не квантового компьютера.

Библиотека для работы с тензорными поездами, python. https://github.com/
oseledets/ttpy.

Облачный доступ к квантовому компьютеру d-wave. https://
cloud.dwavesys.com/leap/.

Подробнее о квантовом отжиге https://docs.dwavesys.com/docs/latest/c_gs_2.html#
id2.

