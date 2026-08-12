---
title: "Метод System::IO::StreamWriter::Write"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::StreamWriter::Write. Записывает указанный символ в поток в C++."
type: docs
weight: 1000
url: /ru/cpp/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) method


Записывает указанный символ в поток.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Символ для записи |

## См. также

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&) method


Записывает все символы из указанного массива в поток.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Массив, содержащий символы для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон символов UTF-16 из указанного массива символов в поток.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
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
## StreamWriter::Write(const char_t *) method


Записывает указанную C-строку в поток.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const char_t * | C-строка для записи |

## См. также

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const SharedPtr\<Object\>\&) method


Записывает строковое представление указанного объекта в поток.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
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
## StreamWriter::Write(const String\&) method


Записывает указанную строку в поток.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для записи |

## См. также

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const System::SharedPtr\<T\>\&) method


Записывает строковое представление указанного объекта в поток.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
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
