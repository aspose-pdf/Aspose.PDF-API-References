---
title: "System::IO::StreamWriter::WriteLine method"
linktitle: "WriteLine"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::StreamWriter::WriteLine method. Записывает символы завершения строки в поток в C++."
type: docs
weight: 1100
url: /ru/cpp/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() method


Записывает символы-разделители строк в поток.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## См. также

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) method


Записывает все символы из указанного массива, за которыми следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Массив, содержащий символы для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон символов UTF‑16 из указанного массива символов, за которым следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Массив, содержащий символы для записи |
| индекс | int32_t | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const char_t *) method


Записывает указанную C‑строку, за которой следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const char_t * | C-строка для записи |

## См. также

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) method


Записывает строковое представление указанного объекта, за которым следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | Объект для записи |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const String\&) method


Записывает указанную строку, за которой следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для записи |

## См. также

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) method


Записывает строковое представление указанного объекта, за которым следуют символы завершения строки, в поток.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const System::SharedPtr\<T\>\& | Объект для записи |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
