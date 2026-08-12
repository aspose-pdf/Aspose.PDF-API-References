---
title: "Método Aspose::Pdf::SaveOptions::set_WarningHandler"
linktitle: "set_WarningHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::SaveOptions::set_WarningHandler. Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continue o Abort. Continue es la acción predeterminada y la operación Save continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Save debe detenerse en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf/saveoptions/set_warninghandler/
---
## SaveOptions::set_WarningHandler method


Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración [ReturnAction](../../returnaction/) que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse.

```cpp
void Aspose::Pdf::SaveOptions::set_WarningHandler(const System::SharedPtr<IWarningCallback> &value)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
