---
title: "Aspose::Pdf::LoadOptions::set_WarningHandler método"
linktitle: "set_WarningHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::set_WarningHandler método. Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum ReturnAction que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf/loadoptions/set_warninghandler/
---
## LoadOptions::set_WarningHandler method


Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../../returnaction/) que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar.

```cpp
void Aspose::Pdf::LoadOptions::set_WarningHandler(const System::SharedPtr<IWarningCallback> &value)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
