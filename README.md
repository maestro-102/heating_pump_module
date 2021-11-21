# heating_pump_module | модуль управления насосами отопления

После установки дополнительных насосов в системе отопления встал вопрос о их управлении и питании, т.к. такую нагрузку на плату управления котлом вешать уже нельзя.

Содержание
----
1. <a href="https://github.com/maestro-102/pulse_divider_for_tachometer#%D1%85%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B8">Характеристики</a>
2. <a href="https://github.com/maestro-102/pulse_divider_for_tachometer#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5">Описание</a>
3. <a href="https://github.com/maestro-102/pulse_divider_for_tachometer#%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B0-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2">Программы для просмотра файлов</a>
4. <a href="https://github.com/maestro-102/pulse_divider_for_tachometer#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0">Структура проекта</a>

Фотографии
----

<a href="https://github.com/maestro-102/electronic_load/blob/master/image/1.jpg" target="_blank">
    <img src="https://github.com/maestro-102/electronic_load/blob/master/image/1.jpg?raw=true" width=30% alt="preview">
</a>

Характеристики
----
Коэффициент деления - 6

Описание
----
Логическое устройство для деления импульсов с определенным коэффициентом. В данной схеме применен коэффициент деления 6. Определенная коммутация выводов микросхемы согласно даташиту позволяет получить другие коэффициенты деления.

Программы для просмотра файлов
-----
1. Sprint Layout 6.0 - для проектирования печатных плат \
Расширение: \*.lay6 \
Ссылка: https://radioaktiv.ru/loads/softf/pcb/27881-sprint-layout-60-rus.html

2. Splan 7.0 - для черчения электрических схем \
Расширение: \*.spl7 \
Ссылка: http://splansoft.ru/

Структура проекта
-----------------

Описание файловой структуры проекта:

    pulse_divider_for_tachometer
    ├── pcb            - печатная плата
    ├── shemas         - схема устройства
    └── README.md          
