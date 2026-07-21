---
title: "Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef"
linktitle: "CssUrlMakingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef. Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente la creación de la URL del CSS referenciado en el documento HTML generado. Por ejemplo, si desea que el CSS referenciado en HTML sea, por ejemplo, \"otherPage.ASPX?CssID=zjjkklj\", entonces esa estrategia personalizada debe devolver \"otherPage.ASPX?CssID=zjjkklj\" en C++."
type: docs
weight: 4800
url: /es/cpp/aspose.pdf/htmlsaveoptions/cssurlmakingstrategy/
---
## CssUrlMakingStrategy typedef


Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente la creación de la URL del CSS referenciado en el documento HTML generado. Por ejemplo, si desea que el CSS sea referenciado en HTML, por ejemplo como "otherPage.ASPX?CssID=zjjkklj", entonces dicha estrategia personalizada debe devolver "otherPage.ASPX?CssID=zjjkklj".

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssUrlRequestInfo>&)>
```


## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
