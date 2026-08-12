---
title: "System::Array::ConvertAll-metod"
linktitle: "ConvertAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::ConvertAll-metod. Skapar ett nytt Array-objekt och fyller det med element från den angivna arrayen som konverteras till OutputType-typen med hjälp av den angivna konverterings-delegaten i C++."
type: docs
weight: 5000
url: /sv/cpp/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method


Skapar ett nytt [Array](../)-objekt och fyller det med element från den angivna arrayen som konverterats till **OutputType**-typen med den angivna konverteringsdelegaten.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


| Parameter | Beskrivning |
| --- | --- |
| InputType | Typen av element i inmatningsarrayen |
| OutputType | Typen av element i den resulterande arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | Ett [Array](../)-objekt |
| converter | Converter\<InputType, OutputType\> | Ett [Converter](../../converter/)-objekt som används för att konvertera varje element i inmatningsarrayen till motsvarande värden av **OutputType**-typen |

### ReturnValue

En ny array som innehåller värden av **OutputType**-typen motsvarande värdena i **input_array**

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method


Skapar ett nytt [Array](../)-objekt och fyller det med element från den angivna arrayen som konverterats till **OutputType**-typen med det angivna konverteringsfunktionsobjektet.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


| Parameter | Beskrivning |
| --- | --- |
| InputType | Typen av element i inmatningsarrayen |
| OutputType | Typen av element i den resulterande arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | Ett [Array](../)-objekt |
| konverterare | std::function\<OutputType(InputType)> | Ett funktionsobjekt som används för att konvertera varje element i inmatningsarrayen till motsvarande värden av **OutputType**-typen |

### ReturnValue

En ny array som innehåller värden av **OutputType**-typen motsvarande värdena i **input_array**

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
