---
title: "System::Uri::MakeRelativeUri metod"
linktitle: "MakeRelativeUri"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri::MakeRelativeUri metod. Avgör skillnaden mellan URI:er som representeras av det aktuella och det angivna Uri‑objektet i C++."
type: docs
weight: 3100
url: /sv/cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri method


Avgör skillnaden mellan URI:er som representeras av det aktuella och det angivna [Uri](../)‑objektet.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | Jämförelsetal |

### ReturnValue

Om värdnamnet och schemat för de URI:er som representeras av det aktuella objektet och **toUri** är samma, returnerar denna metod en relativ [Uri](../) som, när den läggs till den aktuella URI‑instansen, ger **toUri**. Om värdnamnet eller schemat är olika, returnerar metoden ett [Uri](../)‑objekt som representerar parametern **uri**.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
