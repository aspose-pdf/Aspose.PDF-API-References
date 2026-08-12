---
title: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef"
linktitle: "ResourceLoadingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef. A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados desde algún lugar. Por ejemplo, durante el uso de Aspose.Pdf en la nube el acceso directo a los archivos referenciados es imposible, y se debe usar código personalizado colocado en un método especial. Este delegado define la firma de dicho método personalizado en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf/loadoptions/resourceloadingstrategy/
---
## ResourceLoadingStrategy typedef


A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados desde algún lugar. Por ejemplo, durante el uso de [Aspose.Pdf](../../) en la nube el acceso directo a los archivos referenciados es imposible, y se debe usar código personalizado colocado en un método especial. Este delegado define la firma de dicho método personalizado.

```cpp
using Aspose::Pdf::LoadOptions::ResourceLoadingStrategy =  System::MulticastDelegate<System::SharedPtr<Aspose::Pdf::LoadOptions::ResourceLoadingResult>(const System::String&)>
```


## Ver también

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
