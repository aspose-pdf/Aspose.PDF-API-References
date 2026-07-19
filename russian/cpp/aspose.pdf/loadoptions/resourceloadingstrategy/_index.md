---
title: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef"
linktitle: "ResourceLoadingStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef. Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.Pdf в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf/loadoptions/resourceloadingstrategy/
---
## ResourceLoadingStrategy typedef


Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании [Aspose.Pdf](../../) в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода.

```cpp
using Aspose::Pdf::LoadOptions::ResourceLoadingStrategy =  System::MulticastDelegate<System::SharedPtr<Aspose::Pdf::LoadOptions::ResourceLoadingResult>(const System::String&)>
```


## См. также

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
