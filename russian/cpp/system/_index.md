---
title: "Пространство имён System"
linktitle: "System"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать пространство имён System в C++."
type: docs
weight: 2800
url: /ru/cpp/system/
---



## Классы

| Класс | Описание |
| --- | --- |
| [Activator](./activator/) | Содержит методы для создания типов объектов. |
| [Array](./array/) | Класс, представляющий структуру данных массива. Объекты этого класса должны создаваться только с помощью функций [System::MakeArray()](./makearray/) и [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [ArrayBase](./arraybase/) | Заглушка для класса [System.Array](./array/) (абстрактный базовый класс для всех массивов). Может быть дополнена функциональностью по запросу. |
| [ArraySegment](./arraysegment/) | Представляет сегмент одномерного массива. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Attribute](./attribute/) | Базовый класс для пользовательских атрибутов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [BitConverter](./bitconverter/) | Содержит методы, выполняющие преобразования последовательности байтов в тип значения и обратно. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом. |
| [Boolean](./boolean/) | Класс, содержащий статические члены типа [System.Boolean](./boolean/) .[Net](../system.net/). |
| [BoxedEnum](./boxedenum/) | Представляет упакованное значение перечисления. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [BoxedValue](./boxedvalue/) | Представляет упакованное значение. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [BoxedValueBase](./boxedvaluebase/) | Базовый класс, определяющий интерфейс и реализующий некоторые фундаментальные методы наследующего класса, представляющего упакованное значение. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Buffer](./buffer/) | Содержит методы, манипулирующие необработанными массивами байтов. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом. |
| [Byte](./byte/) | Содержит методы для работы с беззнаковым 8-битным целым числом. |
| [Char](./char/) | Предоставляет методы для манипуляции символами, представленными в виде кодовых единиц UTF-16. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом. |
| [Comparison](./comparison/) | Представляет указатель на метод, сравнивающий два объекта одного типа. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Console](./console/) | Предоставляет методы вывода данных в стандартный поток вывода. Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры никаким способом. |
| [ConsoleOutput](./consoleoutput/) | Представляет стандартный поток вывода. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [DateTime](./datetime/) | Представляет конкретное значение даты и времени в континууме времени. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [DateTimeOffset](./datetimeoffset/) | Содержит дату и время суток относительно всемирного координированного времени (UTC). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [DBNull](./dbnull/) | Представляет несуществующее значение. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Decimal](./decimal/) | Представляет десятичное число. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) реализация класса. Позволяет объявлять специализации BoxingValue без дублирования общего кода. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Представляет указатель на функцию, метод или функциональный объект. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [DynamicWeakPtr](./dynamicweakptr/) | Класс умного указателя, который отслеживает режимы указателей шаблонных аргументов хранимого объекта и обновляет их после каждого присваивания. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по константной ссылке. |
| [EnumValues](./enumvalues/) | Предоставляет метаинформацию о константах перечисления типа **E**. |
| [EnumValuesBase](./enumvaluesbase/) | Базовый класс для класса, представляющего метаинформацию типа перечисления. |
| [EventArgs](./eventargs/) | Базовый класс для классов, представляющих контекст, который передаётся подписчикам событий при срабатывании события. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [ExceptionWrapper](./exceptionwrapper/) | Шаблон, представляющий обёртку исключений, производных от класса [Exception](./exception/). |
| [FlagsAttribute](./flagsattribute/) | Указывает, что перечисление может рассматриваться как битовое поле; то есть как набор. |
| [Func](./func/) | Функциональный делегат. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [GC](./gc/) | Представляет эмулированную сборку мусора, которая больше похожа на заглушку и фактически ничего не делает. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом. |
| [Guid](./guid/) | Представляет глобальный уникальный идентификатор. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [IAsyncResult](./iasyncresult/) | Представляет статус асинхронной операции. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [ICloneable](./icloneable/) | Определяет метод, который позволяет клонировать объект — создавать копию объекта. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IComparable](./icomparable/) | Определяет метод, сравнивающий два объекта. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IConvertible](./iconvertible/) | Определяет методы, преобразующие значение реализующего ссылочного или значимого типа в тип среды выполнения Common Language Runtime, имеющий эквивалентное значение. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [ICustomFormatter](./icustomformatter/) | Определяет метод, выполняющий пользовательское форматирование строкового представления значения, представленного указанным объектом. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IDisposable](./idisposable/) | Определяет метод, освобождающий ресурсы, принадлежащие текущему объекту. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IEquatable](./iequatable/) | Определяет метод, определяющий равенство двух объектов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IFormatProvider](./iformatprovider/) | Определяет метод, предоставляющий информацию о форматировании. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IFormattable](./iformattable/) | Определяет метод, форматирующий значение текущего объекта с использованием указанной строки формата и поставщика формата. |
| [Index](./index/) | Представляет индекс в коллекции. Индекс может быть от начала или от конца. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Int16](./int16/) | Содержит методы для работы с 16-битным целым числом. |
| [Int32](./int32/) | Содержит методы для работы с 32-битным целым числом. |
| [Int64](./int64/) | Содержит методы для работы с 64-битным целым числом. |
| [LockContext](./lockcontext/) | Объект‑охранник, реализующий оператор C# lock(). |
| [MarshalByRefObject](./marshalbyrefobject/) | Обеспечивает доступ к объектам через границы доменов приложений в приложениях с включённым удалённым вызовом. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Представляет коллекцию делегатов. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Nullable](./nullable/) | Предварительное объявление. |
| [NullableUtils](./nullableutils/) | Представляет статический класс C# [System.Nullable](./nullable/) (без аргументов типа). Невозможно использовать оригинальное имя из‑за невозможности перегрузки шаблонов классов в C++. Поддерживает тип значения, которому можно присвоить null. Этот класс нельзя наследовать. |
| [Object](./object/) | Базовый класс, позволяющий использовать методы, доступные для класса [System.Object](./object/) в C#. Все нетривиальные классы, используемые в переводимой среде, должны наследовать его. |
| [ObjectExt](./objectext/) | Предоставляет статические методы, эмулирующие методы C# [Object](./object/) вызываемые для не‑Object типов C++ (строки, числа и т.д.). Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры ни при каких обстоятельствах. |
| [ObjectType](./objecttype/) | Предоставляет статические методы, реализующие геттеры объектного типа. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры ни при каких обстоятельствах. |
| [OperatingSystem](./operatingsystem/) | Представляет конкретную операционную систему и предоставляет информацию о ней. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Random](./random/) | Представляет псевдослучайный генератор чисел. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Range](./range/) | Представляет диапазон с начальным и конечным индексом. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [ReadOnlySpan](./readonlyspan/) | Перенаправление для использования внутри класса [Span](./span/). |
| [ScopedCulture](./scopedculture/) | Представляет культуру, используемую в области. |
| [SmartPtr](./smartptr/) | Класс-указатель для обёртывания типов, выделяемых в куче. Используйте его для управления памятью классов, наследующих [Object](./object/). Этот тип указателя следует семантике интрузивных указателей. Счётчик ссылок хранится либо в самом [Object](./object/), либо в структуре счётчика, тесно привязанной к экземпляру [Object](./object/). В любом случае все экземпляры [SmartPtr](./smartptr/) образуют единую группу владения независимо от способа их создания, что отличается от поведения класса std::shared_ptr. Преобразование сырого указателя в [SmartPtr](./smartptr/) безопасно, если существуют другие экземпляры [SmartPtr](./smartptr/), удерживающие совместные ссылки на тот же объект. Экземпляр класса [SmartPtr](./smartptr/) может находиться в одном из двух состояний: совместный указатель и слабый указатель. Чтобы объект оставался живым, количество совместных ссылок на него должно быть положительным. И слабые, и совместные указатели могут использоваться для доступа к объекту (вызов методов, чтение или запись полей и т.д.), но слабые указатели не участвуют в подсчёте совместных ссылок. [Object](./object/) удаляется, когда последний «совместный» указатель [SmartPtr](./smartptr/) к нему уничтожается. Поэтому убедитесь, что этого не происходит, когда нет других совместных указателей [SmartPtr](./smartptr/) на объект, например во время конструирования или разрушения объекта. Используйте охранные объекты System::Object::ThisProtector (в C++ коде) или атрибуты CppCTORSelfReference или CppSelfReference (в переводимом C# коде) для исправления этой проблемы. Аналогично, разорвите циклические ссылки, используя класс указателя [System::WeakPtr](./weakptr/) или режим указателя [System::SmartPtrMode::Weak](./smartptrmode/) (в C++ коде) или атрибут CppWeakPtr (в переводимом C# коде). Если два или более объектов ссылаются друг на друга с помощью «совместных» указателей, они никогда не будут удалены. Если тип указателя (слабый или совместный) должен переключаться во время выполнения, используйте метод [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) или класс [System::DynamicWeakPtr](./dynamicweakptr/). Класс [SmartPtr](./smartptr/) не содержит виртуальных методов. Наследовать его следует только если вы создаёте собственную стратегию управления памятью. Этот тип — указатель для управления удалением другого объекта. Его следует выделять в стеке и передавать в функции по значению или по константной ссылке. |
| [SmartPtrInfo](./smartptrinfo/) | Сервисный класс для тестирования и изменения содержимого [SmartPtr](./smartptr/) без знания конечного типа. Используется для сборки мусора и обнаружения циклических ссылок и т.п. Считайте его «указателем на указатель». Мы не можем использовать базовый тип [SmartPtr](./smartptr/), так как его нет; вместо этого используем этот «инфо» класс. |
| [Span](./span/) | Представляет непрерывный регион произвольной памяти, аналогичный std::span из C++20. |
| [String](./string/) | Класс [String](./string/), используемый по всей библиотеке. Является заменой C# [System.String](./string/) при переводе кода. По причинам оптимизации не считается подклассом [Object](./object/). Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [StringComparer](./stringcomparer/) | Сравнивает строки, используя различные режимы сравнения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [StringHashCompiletime](./stringhashcompiletime/) | Вспомогательный класс, генерирующий хеш‑значение из C‑строки. |
| [TimeSpan](./timespan/) | Представляет интервал времени. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [TimeZone](./timezone/) | Представляет часовой пояс. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [TimeZoneInfo](./timezoneinfo/) | Представляет информацию, описывающую конкретный часовой пояс. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [Tuple](./tuple/) | Класс, представляющий структуру кортежа. Максимальное количество элементов — 8. |
| [TupleFactory](./tuplefactory/) | Предоставляет статические методы для создания объектов кортежа. |
| [TypeInfo](./typeinfo/) | Представляет конкретный тип и предоставляет информацию о нём. |
| [Uri](./uri/) | Унифицированный идентификатор ресурса. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [UriBuilder](./uribuilder/) | Предоставляет методы для создания и изменения универсальных идентификаторов ресурсов (URI). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [UriParser](./uriparser/) | Используется для разбора новой схемы URI. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](./makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](./smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [UriShim](./urishim/) | Сервисный класс. |
| [ValueTuple](./valuetuple/) | Класс, представляющий структуру [ValueTuple](./valuetuple/). |
| [ValueType](./valuetype/) | Базовый класс для типов‑значений с наследованием от [Object](./object/), усечённым в целях повышения производительности. Этот тип следует размещать в стеке и передавать функциям по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Version](./version/) | Представляет номер версии. Этот тип следует размещать в стеке и передавать функциям по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Подкласс [System::SmartPtr](./smartptr/), который устанавливает себя в режим слабой ссылки при конструировании. Обратите внимание, что этот класс не гарантирует, что его экземпляр всегда будет оставаться в слабом режиме, так как метод [set_Mode()](./smartptr/set_mode/) остаётся доступным. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке. |
| [WeakReference](./weakreference/) | Представляет слабую ссылку, которая ссылается на объект, но при этом позволяет удалить этот объект. |
| [WeakReference< T >](./weakreference_t_/) | Представляет слабую ссылку, которая ссылается на объект, но при этом позволяет удалить этот объект. |
| [WeakReference<>](./weakreference__/) | Представляет слабую ссылку, которая ссылается на объект, но при этом позволяет удалить этот объект. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Перечисление, содержащее значения, представляющие различные форматы данных, закодированных в base‑64. |
| [DateTimeKind](./datetimekind/) | Значения перечисления, представляющие виды даты и времени. |
| [DayOfWeek](./dayofweek/) | Перечисление, представляющее день недели. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Указывает расположение переменной окружения. |
| [MidpointRounding](./midpointrounding/) | Определяет поведение функций округления. |
| [PlatformID](./platformid/) | Представляет платформу операционной системы. |
| [SmartPtrMode](./smartptrmode/) | Тип указателя [SmartPtr](./smartptr/): слабый или совместный. Определяет, учитывается ли указатель при решении, удалять объект или нет. |
| [StringComparison](./stringcomparison/) | Определяет стиль сравнения строк. |
| [StringSplitOptions](./stringsplitoptions/) | Определяет поведение разбиения строки. |
| [TypeCode](./typecode/) | Представляет тип объекта. |
| [UriComponents](./uricomponents/) | Представляет компоненты URI. |
| [UriFormat](./uriformat/) | Указывает, как происходит экранирование URI. |
| [UriHostNameType](./urihostnametype/) | Представляет тип имени хоста. |
| [UriKind](./urikind/) | Представляет виды URI. |
| [UriPartial](./uripartial/) | Представляет части URI для метода [Uri.GetLeftPart](./uri/getleftpart/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Action](./action/) | Тип делегата, ссылающийся на методы без возвращаемого значения. |
| [AggregateException](./aggregateexception/) |  |
| [ArrayPtr](./arrayptr/) | Псевдоним типа «указатель на массив». |
| [AsyncCallback](./asynccallback/) | Тип делегата, представляющий метод, вызываемый по завершении асинхронной операции. |
| [BadImageFormatException](./badimageformatexception/) | Исключение, которое выбрасывается, когда образ файла динамической библиотеки (DLL) или исполняемой программы недействителен. Никогда не оборачивайте экземпляры класса [BadImageFormatException](./badimageformatexception/) в [System::SmartPtr](./smartptr/). |
| [ByteArrayPtr](./bytearrayptr/) | Псевдоним объекта умного указателя, указывающего на массив беззнаковых 8‑битных целых. |
| [Converter](./converter/) | Представляет указатель на вызываемую сущность, принимающую один аргумент типа **TInput** и возвращающую значение типа **TOutput**. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/). |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::DecoderFallback](../system.text/decoderfallback/). |
| [DecoderPtr](./decoderptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::Decoder](../system.text/decoder/). |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/). |
| [DirectoryInfoPtr](./directoryinfoptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::DirectoryInfo](../system.io/directoryinfo/). |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/). |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::EncoderFallback](../system.text/encoderfallback/). |
| [EncoderPtr](./encoderptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::Encoder](../system.text/encoder/). |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/). |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/). |
| [EncodingInfoPtr](./encodinginfoptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::EncodingInfo](../system.text/encodinginfo/). |
| [EncodingPtr](./encodingptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Text::Encoding](../system.text/encoding/). |
| [Event](./event/) | Представляет событие — механизм, с помощью которого подписчики уведомляются о событии интереса посредством вызова делегата. |
| [EventArgsPtr](./eventargsptr/) | Разделяемый указатель на экземпляр класса [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | Представляет метод, реагирующий на событие и обрабатывающий его. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](./smartptr/) для управления объектами этого типа. |
| [Exception](./exception/) | Псевдоним, используемый вместо Details::Exception. |
| [ExceptionPtr](./exceptionptr/) | Типовой псевдоним, используемый обёртками исключений. |
| [FileInfoPtr](./fileinfoptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::FileInfo](../system.io/fileinfo/). |
| [FileStreamPtr](./filestreamptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::FileStream](../system.io/filestream/). |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::FileSystemInfo](../system.io/filesysteminfo/). |
| [FunctionPtr](./functionptr/) | Псевдоним типа функции с соглашением вызова по умолчанию. |
| [IAsyncResultPtr](./iasyncresultptr/) | Разделяемый указатель на [IAsyncResult](./iasyncresult/). |
| [IFormatProviderPtr](./iformatproviderptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IFormatProvider](./iformatprovider/). |
| [MakeConstRef_t](./makeconstref_t/) | Вспомогательный тип для модификатора [MakeConstRef](./makeconstref/). |
| [MemoryStreamPtr](./memorystreamptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::MemoryStream](../system.io/memorystream/). |
| [Predicate](./predicate/) | Представляет указатель на предикат — вызываемую сущность, принимающую один аргумент и возвращающую значение типа bool. |
| [RTaskPtr](./rtaskptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/). |
| [SharedPtr](./sharedptr/) | Псевдоним умного указателя, широко используемого в библиотеке. |
| [StreamPtr](./streamptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::Stream](../system.io/stream/). |
| [StreamReaderPtr](./streamreaderptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::StreamReader](../system.io/streamreader/). |
| [StreamWriterPtr](./streamwriterptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::IO::StreamWriter](../system.io/streamwriter/). |
| [StringComparerPtr](./stringcomparerptr/) | Псевдоним разделяемого указателя на экземпляр класса [StringComparer](./stringcomparer/). |
| [SystemException](./systemexception/) |  |
| [TaskPtr](./taskptr/) | Псевдоним умного указателя, указывающего на экземпляр класса [System::Threading::Tasks::Task](../system.threading.tasks/task/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Псевдоним разделяемого указателя на экземпляр класса [TimeZoneInfo](./timezoneinfo/). |
| [TimeZonePtr](./timezoneptr/) | Разделяемый указатель на экземпляр класса [TimeZone](./timezone/). |
## Functions

| Функция | Описание |
| --- | --- |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Build | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| BuildArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| BuildObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CheckedCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| const_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConstCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Discard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| dynamic_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForceStaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForEachMemberGVName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GEqual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| get_pointer | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Greater | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| InitObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_parametrized_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_vp_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNegativeInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNull | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPositiveInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| LEqual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Less | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeScopeGuard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerable | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerator | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MemberwiseClone | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| SafeInvoke | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Set | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| static_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| TieTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
