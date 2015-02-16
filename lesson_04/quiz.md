## Сопоставление с образцом используется для:

присвоения значения переменной

извлечения значения из переменной

выбора ветки кода для выполнения

безусловного перехода


## Связанная переменная

имеет значение

не имеет значения

в сопоставлении с образцом может использоваться слева от =

в сопоставлении с образцом может использоваться справа от =


## Несвязанная переменная

имеет значение

не имеет значения

в сопоставлении с образцом может использоваться слева от =

в сопоставлении с образцом может использоваться справа от =


## Если шаблон не совпал, то

выбрасывается исключение

возвращается false

выполняется другая ветка кода

компилятор не позволит написать такой шаблон


## Функция

может иметь несколько клозов

может не иметь ни одного клоза

должна иметь только один клоз

может иметь гарды


## При вызове функции

выполняются все клозы, для которых аргументы подходят по шаблону

выполняется только один клоз, для которого аргументы подходят по шаблону

выбрасывается исключение, если аргументы не подошли ни в одном клозе

выполняется последный клоз, если аргументы не подошли ко всем клозам выше


## Если все выражения в гарде вычислились в true, то

гард разрешает выполнение данной ветки кода

гард не разрешает выполнение данной ветки кода


## Отметьте выражения, разрешенные для использования в гарде

Val > 5 andalso Val < 10

length(List) > 1

is_boolean(Val)

tuple_size(Val) == 2

throw(error)

my_module:my_fun(Val)


## в case выражении могут использоваться

шаблоны

гарды

клозы

вложенные case выражения


## в if выражении могут использоваться

шаблоны

гарды

клозы

вложенные if выражения