---
title: "System::Reflection::BindingFlags enum"
linktitle: "BindingFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::BindingFlags enum. Definierar medlemmar och typer för uppslagslägen och bindningar i C++."
type: docs
weight: 1100
url: /sv/cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Definierar medlemmar och typer för uppslagningslägen och bindningar.

```cpp
enum class BindingFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Inga speciella alternativ. |
| IgnoreCase | 1 | Ignorera skiftlägeskänslighet i namn vid sökning efter objekt. |
| DeclaredOnly | 2 | Sök endast efter medlemmar som deklarerats i typen och inte i basklasser. |
| Instans | 4 | Titta igenom instansmedlemmar. |
| Statisk | 8 | Titta igenom statiska medlemmar. |
| Publik | 16 | Titta igenom offentliga medlemmar. |
| NonPublic | 32 | Titta igenom icke-publika medlemmar. |
| FlattenHierarchy | 64 | Titta igenom basklassens offentliga och skyddade statiska medlemmar. |
| InvokeMethod | 256 | Anropar metod. |
| CreateInstance | 512 | Skapar reflekterad typinstans. |
| GetField | 1024 | Hämtar fältvärde. |
| SetField | 2048 | Sätter fältvärde. |
| GetProperty | 4096 | Hämtar egenskapsvärde. |
| SetProperty | 8192 | Sätter egenskapsvärde. |
| PutDispProperty | 16384 | Sätter COM-egenskap. |
| PutRefDispProperty | 32768 | Sätter COM-referensegenskap. |
| ExactBinding | 65536 | Typbindning måste vara exakt, utan några typändringar. |
| SuppressChangeType | 131072 | Stöds inte. |
| OptionalParamBinding | 262144 | Väljer överlagring baserat på antalet argument. |
| IgnoreReturn | 16777216 | Ignorerar COM-interop returvärde. |

## Se även

* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
