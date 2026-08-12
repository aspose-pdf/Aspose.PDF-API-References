---
title: "System::IO::StreamWriter::Write metod"
linktitle: "Write"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StreamWriter::Write metod. Skriver det angivna tecknet till strömmen i C++."
type: docs
weight: 1000
url: /sv/cpp/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) method


Skriver det angivna tecknet till strömmen.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char_t | Tecknet att skriva |

## Se även

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&) method


Skriver alla tecken från den angivna arrayen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Arrayen som innehåller tecknen att skriva |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Skriver det angivna delintervallet av UTF-16‑tecken från den angivna teckenarrayen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | int32_t | Ett 0-baserat index för elementet i **buffer** där delområdet att skriva börjar |
| count | int32_t | Antalet tecken i delområdet att skriva; -1 anger att delområdet slutar där **buffer**-arrayen slutar |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const char_t *) method


Skriver den angivna c‑strängen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const char_t * | c-strängen att skriva |

## Se även

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const SharedPtr\<Object\>\&) method


Skriver strängrepresentationen av det angivna objektet till strömmen.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SharedPtr\<Object\>\& | Objektet att skriva |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const String\&) method


Skriver den angivna strängen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att skriva |

## Se även

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::Write(const System::SharedPtr\<T\>\&) method


Skriver strängrepresentationen av det angivna objektet till strömmen.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen på objektet |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const System::SharedPtr\<T\>\& | Objektet att skriva |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
