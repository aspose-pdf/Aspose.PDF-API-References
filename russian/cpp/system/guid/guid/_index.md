---
title: "Конструктор System::Guid::Guid"
linktitle: "Guid"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Guid::Guid. Создаёт объект, представляющий GUID, состоящий только из нулей, в C++."
type: docs
weight: 100
url: /ru/cpp/system/guid/guid/
---
## Guid::Guid() constructor


Создаёт объект, представляющий GUID, состоящий только из нулей.

```cpp
System::Guid::Guid()
```

## См. также

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructor


Создаёт объект, представляющий GUID, указанный в виде массива беззнаковых 8‑битных целых значений.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| b | const ArrayPtr\<uint8_t\>\& | Массив байтов, содержащий отдельные байты GUID |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const Guid\&) constructor


Создаёт объект, представляющий тот же GUID, что и указанный объект.

```cpp
System::Guid::Guid(const Guid &guid)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | const Guid\& | Объект [Guid](../), из которого копировать значение GUID |

## См. также

* Class [Guid](../)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const String\&) constructor


Создаёт объект, представляющий GUID, указанный в виде строки.

```cpp
System::Guid::Guid(const String &g)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| g | const String\& | Строковое представление GUID, которое будет представлено создаваемым объектом |

## См. также

* Class [String](../../string/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructor


Создаёт объект, представляющий GUID, указанный в виде представления массива беззнаковых 8‑битных целых значений.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| b | const System::Details::ArrayView\<uint8_t\>\& | Массив байтов, содержащий отдельные байты GUID |

## См. также

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructor


Создаёт экземпляр класса [Guid](../) из указанных компонентов GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | int32_t | Биты 0-31 GUID |
| b | int16_t | Биты 32-47 GUID |
| c | int16_t | Биты 48-63 GUID |
| d | const ArrayPtr\<uint8_t\>\& | Массив байтов, содержащий биты 64-127 GUID |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructor


Создаёт экземпляр класса [Guid](../) из указанных компонентов GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | int32_t | Биты 0-31 GUID |
| b | int16_t | Биты 32-47 GUID |
| c | int16_t | Биты 48-63 GUID |
| d | const System::Details::ArrayView\<uint8_t\>\& | Представление массива байтов, содержащее биты 64-127 GUID |

## См. также

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Создаёт экземпляр класса [Guid](../) из указанных беззнаковых целых чисел и байтов.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | int32_t | Биты 0-31 GUID |
| b | int16_t | Биты 32-47 GUID |
| c | int16_t | Биты 48-63 GUID |
| d | uint8_t | Биты 64-71 GUID |
| e | uint8_t | Биты 72-79 GUID |
| f | uint8_t | Биты 80-87 GUID |
| g | uint8_t | Биты 88-95 GUID |
| h | uint8_t | Биты 96-103 GUID |
| i | uint8_t | Биты 104-111 GUID |
| j | uint8_t | Биты 112-119 GUID |
| k | uint8_t | Биты 120-127 GUID |

## См. также

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Создаёт экземпляр класса [Guid](../) из указанных беззнаковых целых чисел и байтов.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | uint32_t | Биты 0-31 GUID |
| b | uint16_t | Биты 32-47 GUID |
| c | uint16_t | Биты 48-63 GUID |
| d | uint8_t | Биты 64-71 GUID |
| e | uint8_t | Биты 72-79 GUID |
| f | uint8_t | Биты 80-87 GUID |
| g | uint8_t | Биты 88-95 GUID |
| h | uint8_t | Биты 96-103 GUID |
| i | uint8_t | Биты 104-111 GUID |
| j | uint8_t | Биты 112-119 GUID |
| k | uint8_t | Биты 120-127 GUID |

## См. также

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
