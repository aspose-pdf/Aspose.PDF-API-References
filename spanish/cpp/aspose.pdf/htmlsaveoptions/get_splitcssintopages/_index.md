---
title: "Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages method"
linktitle: "get_SplitCssIntoPages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages method. Cuando se selecciona el modo multipágina (es decir, ''SplitIntoPages'' es ''true''), este atributo define si debe crearse un archivo CSS separado para cada página HTML resultante. Por defecto este atributo es false, por lo que se crea un único CSS común grande para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un único CSS grande, porque en el caso anterior las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración solo debe usarse cuando le interese procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor crítico en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.pdf/htmlsaveoptions/get_splitcssintopages/
---
## HtmlSaveOptions::get_SplitCssIntoPages method


Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), este atributo define si se debe crear un archivo CSS separado para cada página HTML resultante. Por defecto, este atributo es false, por lo que se crea un único CSS común para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un único CSS grande, porque en el primer caso las clases CSS se duplican en varios archivos CSS para cada página. Por lo tanto, esta configuración solo debería usarse cuando estés interesado en procesar cada página HTML de forma independiente en el futuro, y por consiguiente el tamaño del CSS de cada página individual sea el factor más crítico.

```cpp
bool Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages() const
```

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
