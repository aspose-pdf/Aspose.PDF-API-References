---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет BoundsCheckableList — обёртку над System.Collections.Generic.List."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Представляет BoundsCheckableList — обёртку над System.Collections.Generic.List.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Инициализирует новый экземпляр класса BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Инициализирует новый экземпляр класса BoundsCheckableList. |

## Методы

| Метод | Описание |
| --- | --- |
| [addItem](#addItem-T-) | Добавляет объект в конец списка System.Collections.Generic.List в зависимости от параметра "boundsCheckMode". |
| [clear](#clear--) | Удаляет все элементы из списка System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Определяет, находится ли элемент в списке System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Копирует весь список System.Collections.Generic.List в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Item](#get_Item-int-) | Получает или задает абзац из коллекции или в коллекцию. |
| [indexOfItem](#indexOfItem-T-) | Ищет указанный объект и возвращает нулевой индекс первого вхождения во весь список System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Вставляет элемент в список System.Collections.Generic.List по указанному индексу. |
| [isReadOnly](#isReadOnly--) | Получает значение, указывающее, является ли коллекция только для чтения. |
| [iterator](#iterator--) | Возвращает перечислитель, который проходит по списку System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Удаляет элемент по указанному индексу в списке System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Удаляет первое вхождение конкретного объекта из списка System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Получает или задает абзац из коллекции или в коллекцию. |
| [size](#size--) | Получает количество элементов, содержащихся в списке System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Инициализирует новый экземпляр класса BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Инициализирует новый экземпляр класса BoundsCheckableList.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| boundsCheckMode |  | Режим проверки границ. |
| containerWidth |  | Ширина контейнера. |
| containerHeight |  | Высота контейнера. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Добавляет объект в конец списка System.Collections.Generic.List в зависимости от параметра "boundsCheckMode".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент |  | Объект, который будет добавлен в конец System.Collections.Generic.List. Значение может быть "null" для ссылочных типов. |

### clear {#clear--}
```
public final void clear()
```

Удаляет все элементы из списка System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Определяет, находится ли элемент в списке System.Collections.Generic.List.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент |  | Объект, который нужно найти в System.Collections.Generic.List. Значение может быть null для ссылочных типов. |

**Returns:**
true, если itemitem найден в System.Collections.Generic.List; иначе false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Копирует весь список System.Collections.Generic.List в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| массив |  | Одномерный System.Array, являющийся получателем элементов, скопированных из System.Collections.Generic.List. System.Array должен иметь индексацию, начинающуюся с нуля. |
| arrayIndex |  | Индекс, начинающийся с нуля, в массиве, с которого начинается копирование. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Получает или задает абзац из коллекции или в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс |  | Индекс абзаца. |

**Returns:**
элемент с указанным индексом.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Ищет указанный объект и возвращает нулевой индекс первого вхождения во весь список System.Collections.Generic.List.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент |  | Объект, который нужно найти в System.Collections.Generic.List. Значение может быть null для ссылочных типов. |

**Returns:**
Нулевой индекс первого вхождения itemitem во всей System.Collections.Generic.List, если найден; иначе –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Вставляет элемент в список System.Collections.Generic.List по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс |  | Нулевой индекс, по которому должен быть вставлен item. |
| элемент |  | Объект для вставки. Значение может быть null для ссылочных типов. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли коллекция только для чтения.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Возвращает перечислитель, который проходит по списку System.Collections.Generic.List.

**Returns:**
Перечислитель для System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в списке System.Collections.Generic.List.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс |  | Нулевой индекс элемента, который нужно удалить. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Удаляет первое вхождение конкретного объекта из списка System.Collections.Generic.List.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент |  | Объект, который нужно удалить из System.Collections.Generic.List. Значение может быть null для ссылочных типов. |

**Returns:**
true, если itemitem успешно удалён; иначе false. Этот метод также возвращает false, если itemitem не найден в System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Получает или задает абзац из коллекции или в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс |  | Индекс абзаца. |

### size {#size--}
```
public final int size()
```

Получает количество элементов, содержащихся в списке System.Collections.Generic.List.

**Returns:**
Количество элементов, содержащихся в System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Обновляет параметр boundsCheckMode для инициализированной коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| boundsCheckMode |  | Режим проверки границ. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Обновляет параметр boundsCheckMode для инициализированной коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| boundsCheckMode |  | Режим проверки границ. |
| containerWidth |  | Ширина контейнера. |
| containerHeight |  | Высота контейнера. |
