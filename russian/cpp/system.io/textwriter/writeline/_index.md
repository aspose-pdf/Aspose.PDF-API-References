---
title: "System::IO::TextWriter::WriteLine метод"
linktitle: "WriteLine"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::TextWriter::WriteLine метод. Записывает символы-разделители строки в поток в C++."
type: docs
weight: 1000
url: /ru/cpp/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() method


Записывает символы-разделители строк в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(bool) method


Записывает строковое представление указанного логического значения, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | bool | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(char_t) method


Записывает указанный символ, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) method


Записывает все символы из указанного массива, за которыми следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Массив, содержащий символы для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон символов UTF‑16 из указанного массива символов, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Массив, содержащий символы для записи |
| индекс | int32_t | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const char_t *) method


Записывает указанную C‑строку, за которой следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const SharedPtr\<Object\>\&) method


Записывает строковое представление указанного объекта, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const SharedPtr\<Object\>\& | Объект для записи |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const String\&, const TArgs\&...) method


Записывает указанные значения, отформатированные согласно указанному формату, за которыми следуют символы завершения строки, в поток.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```


| Параметр | Описание |
| --- | --- |
| TArgs | Список типов значений для записи |

| Параметр | Тип | Описание |
| --- | --- | --- |
| формат | const String\& | Формат строки |
| args | const TArgs\&... | Значения для записи |

## См. также

* Class [String](../../../system/string/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const String\&) method


Записывает указанную строку, за которой следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для записи |

## См. также

* Class [String](../../../system/string/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(const TypeInfo\&) method


Записывает строковое представление указанного объекта [TypeInfo](../../../system/typeinfo/), за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const TypeInfo\& | Объект для записи |

## См. также

* Class [TypeInfo](../../../system/typeinfo/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(Decimal) method


Записывает строковое представление указанного объекта [Decimal](../../../system/decimal/), за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | Decimal | Объект для записи |

## См. также

* Class [Decimal](../../../system/decimal/)
* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(double) method


Записывает строковое представление указанного значения двойной точности с плавающей запятой, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(float) method


Записывает строковое представление указанного значения с одинарной точностью, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(int) method


Записывает строковое представление указанного 32‑разрядного целочисленного значения, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(int64_t) method


Записывает строковое представление указанного 64‑разрядного целочисленного значения, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int64_t | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(uint32_t) method


Записывает строковое представление указанного беззнакового 32‑разрядного целого значения, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | uint32_t | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextWriter::WriteLine(uint64_t) method


Записывает строковое представление указанного беззнакового 64‑разрядного целого значения, за которым следуют символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | uint64_t | Значение для записи |

## См. также

* Class [TextWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
