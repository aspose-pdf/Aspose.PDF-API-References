---
title: "System::Uri::MakeRelative método"
linktitle: "MakeRelative"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Uri::MakeRelative método. Determina la diferencia entre dos instancias de Uri en C++."
type: docs
weight: 3000
url: /es/cpp/system/uri/makerelative/
---
## Uri::MakeRelative method


Determina la diferencia entre dos instancias de [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| toUri | const SharedPtr\<Uri\>\& | El URI para comparar con el URI actual |

### ReturnValue

Si el nombre de host y el esquema de los URIs representados por el objeto actual y **toUri** son los mismos, entonces este método devuelve un [String](../../string/) que representa un [Uri](../) relativo, que al añadirse a la instancia del URI actual produce **toUri**. Si el nombre de host o el esquema son diferentes, entonces este método devuelve un [String](../../string/) que representa el parámetro **uri**.

## Ver también

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
