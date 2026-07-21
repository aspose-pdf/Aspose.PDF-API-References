---
title: "Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy typedef"
linktitle: "CssSavingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Typedef Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy. Puede asignar a esta propiedad una estrategia personalizada que implemente el procesamiento y/o guardado de una parte de CSS que se creó durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) debe realizarse en ese código personalizado en C++."
type: docs
weight: 4700
url: /es/cpp/aspose.pdf/htmlsaveoptions/csssavingstrategy/
---
## CssSavingStrategy typedef


Puede asignar a esta propiedad una estrategia personalizada que implemente el procesamiento y/o guardado de una parte de CSS que se creó durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) debe realizarse en ese código personalizado.

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy =  System::MulticastDelegate<void(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssSavingInfo>&)>
```


## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
