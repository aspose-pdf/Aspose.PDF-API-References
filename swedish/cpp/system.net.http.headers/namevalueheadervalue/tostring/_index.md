---
title: "System::Net::Http::Headers::NameValueHeaderValue::ToString metod"
linktitle: "ToString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::NameValueHeaderValue::ToString metod. Analog till C# Object.ToString()-metoden. Gör det möjligt att konvertera anpassade objekt till sträng i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const method


Analog till C# [Object.ToString()](../../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### ReturnValue

[String](../../../system/string/) representation as provided by final class.

## Se även

* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) method


Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värden | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | Samlingen av NameValueHeaderValue-klassens instanser. |
| separator | char16_t | En strängseparator. |
| leadingSeparator | bool | Värdet som indikerar om strängseparatorn måste läggas till före det första samlingsobjektet. |

### ReturnValue

En strängrepresentation av samlingen av NameValueHeaderValue-klassens instanser.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) method


Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värden | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | Samlingen av NameValueHeaderValue-klassens instanser. |
| separator | char16_t | En strängseparator. |
| leadingSeparator | bool | Värdet som indikerar om strängseparatorn måste läggas till före det första samlingsobjektet. |
| destination | System::SharedPtr\<Text::StringBuilder\> | En instans där en strängrepresentation kommer att tilldelas. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
