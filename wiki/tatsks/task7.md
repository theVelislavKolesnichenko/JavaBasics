# Задача

I. Да се състави интерфейс ShopReader за четене от файл.
Метод: void readShopData()

II. Да се състави клас "Stock", пакетен достъп, имплементиращ Comparable

Частни полета:
    
    - производител (manufacturer)
    
    - наличност (count)
    
    - цена (price)

Публични членове. Конструктори:

II.1 Подразбиращ се

Експлицитни:

II.2. По производител и наличност;

II.3. Производител.

Методи:

II. 4 Четене и презапис на полетата

II.5 Имплементиране на интерфейса (по избор)

II.6. Сравнение за еквивалентност

II.7 За стрингова интерпретация

III.Да се състави клас "InternalComponent", имплементиращ Stock. 

Частни полета:

- честота (frequency)

Публични членове. Конструктори:

IV.1 Експлицитен с параметър име на файл с данни 
Методи:

IV.2. Стрингова имплементация

IV.Да се състави клас "ExternalComponent", наследява Stock. 

Частни полета:

- инчове (inch)

Публични членове. Конструктори:

IV.1 Експлицитен с параметър име на файл с данни 
Методи:

IV.2. Стрингова имплементация

V.Да се състави клас "Shop", наследява ShopReader. 

Частни полета:

Име на файл, в който са записани продуктите
Списък от продукти, тип List, от обекти от клас II.

Публични членове. Конструктори:

V.1 Експлицитен с параметър име на файл с данни 
Методи:

V.2. Стрингова имплементация

V.3. Имплементация на интерфейса

V.4. Намиране на производителя с най-много продукти връща име(на) на производител(и)

V.5. Намиране на артикул с най-добра честота връща честотата

VI. Главна функция

VI.1 Създава обект от клас V. чрез файл, извежда го на конзолния изход

VI.2 Намиране на производителя с най-много продукти

VI.3 Намиране на артикул с най-добра честота

VI.6 Обработва изключения

```

Примерен файл –
Формат:

type1 <производител> <наличност> <цена> <честота>

type2 <производител> <наличност> <цена> <инчове>

```
