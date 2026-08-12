---
title: "System::Uri::MakeRelativeUri método"
linktitle: "MakeRelativeUri"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Uri::MakeRelativeUri método. Determina la diferencia entre los URIs representados por el objeto actual y los objetos Uri especificados en C++."
type: docs
weight: 3100
url: /es/cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri method


Determina la diferencia entre los URIs representados por el actual y los objetos [Uri](../) especificados.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | El comparando |

### ReturnValue

Si el nombre de host y el esquema de los URIs representados por el objeto actual y **toUri** son los mismos, entonces este método devuelve un [Uri](../) relativo que, al añadirse a la instancia de URI actual, produce **toUri**. Si el nombre de host o el esquema son diferentes, entonces este método devuelve un objeto [Uri](../) que representa el parámetro **uri**.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
