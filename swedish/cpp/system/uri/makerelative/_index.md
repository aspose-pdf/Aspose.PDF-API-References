---
title: "System::Uri::MakeRelative-metod"
linktitle: "MakeRelative"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri::MakeRelative-metod. Bestämmer skillnaden mellan två Uri-instansers i C++."
type: docs
weight: 3000
url: /sv/cpp/system/uri/makerelative/
---
## Uri::MakeRelative method


Bestämmer skillnaden mellan två [Uri](../)-instanser.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| toUri | const SharedPtr\<Uri\>\& | URI:n att jämföra med den aktuella URI:n |

### ReturnValue

Om värdnamnet och schemat för de URI:er som representeras av det aktuella objektet och **toUri** är samma, returnerar denna metod en [String](../../string/) som representerar en relativ [Uri](../), som när den läggs till den aktuella URI-instansen ger **toUri**. Om värdnamnet eller schemat är olika, returnerar metoden en [String](../../string/) som representerar **uri**-parametern.

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
