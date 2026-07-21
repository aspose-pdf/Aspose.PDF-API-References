---
title: "Aspose::Pdf::LoadOptions::get_WarningHandler método"
linktitle: "get_WarningHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::get_WarningHandler método. Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum ReturnAction que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf/loadoptions/get_warninghandler/
---
## LoadOptions::get_WarningHandler method


Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../../returnaction/) que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::LoadOptions::get_WarningHandler() const
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
