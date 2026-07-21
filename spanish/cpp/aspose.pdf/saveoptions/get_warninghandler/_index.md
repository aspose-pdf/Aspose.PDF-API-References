---
title: "Aspose::Pdf::SaveOptions::get_WarningHandler método"
linktitle: "get_WarningHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::SaveOptions::get_WarningHandler método. Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf/saveoptions/get_warninghandler/
---
## SaveOptions::get_WarningHandler method


Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración [ReturnAction](../../returnaction/) que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::SaveOptions::get_WarningHandler() const
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
