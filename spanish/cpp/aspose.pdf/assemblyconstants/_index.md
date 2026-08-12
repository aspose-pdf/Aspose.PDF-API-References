---
title: "Clase Aspose::Pdf::AssemblyConstants"
linktitle: "AssemblyConstants"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::AssemblyConstants class. Define las constantes que participan en la verificación de licencia del componente. Estos solían definirse directamente como atributos de ensamblado, pero los trasladé a una clase separada porque en .NET Compact Framework no puedo acceder a los atributos de ensamblado. Ahora el código de licenciamiento, cuando se compila para .NET Compact Framework, usa estas constantes en lugar de los atributos de ensamblado en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf/assemblyconstants/
---
## AssemblyConstants class


Define las constantes que participan en la verificación de licencia del componente. Estas solían definirse directamente como atributos de ensamblado, pero las trasladé a una clase separada porque en .NET Compact Framework no puedo acceder a los atributos de ensamblado. Ahora el código de licenciamiento, cuando se compila para .NET Compact Framework, utiliza estas constantes en lugar de los atributos de ensamblado.

```cpp
class AssemblyConstants : public System::Object
```

## Campos

| Campo | Descripción |
| --- | --- |
| static [Family](./family/) |  |
| static [MicrosoftExtensionsDataIngestionMarkdigVersion](./microsoftextensionsdataingestionmarkdigversion/) |  |
| static [MicrosoftExtensionsDataIngestionVersion](./microsoftextensionsdataingestionversion/) |  |
| static [MicrosoftMLTokenizersDataCl100kBaseVersion](./microsoftmltokenizersdatacl100kbaseversion/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | El productor del archivo [Pdf](../). |
| static [PRODUCT](./product/) |  |
| static [Product](./product/) | Esto se usa por el código de licenciamiento de **Aspose** para verificar que la licencia es para el producto correcto. |
| static [ReleaseDate](./releasedate/) | Esto se usa por el código de licenciamiento de **Aspose** para comprobar la expiración de la suscripción. Debes establecer esto en la fecha en que publiques una versión o una corrección urgente. |
| static [Title](./title/) |  |
| static [VERSION](./version/) |  |
| static [Version](./version/) | La versión del ensamblado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
