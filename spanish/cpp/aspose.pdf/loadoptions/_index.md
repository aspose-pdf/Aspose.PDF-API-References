---
title: "Aspose::Pdf::LoadOptions class"
linktitle: "LoadOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions class. El tipo LoadOptions mantiene el nivel de abstracción sobre opciones de carga individuales en C++."
type: docs
weight: 10500
url: /es/cpp/aspose.pdf/loadoptions/
---
## LoadOptions class


[LoadOptions](./) type holds level of abstraction on individual load options.

```cpp
class LoadOptions : public virtual System::Object
```

## Nested classes

* Class [ResourceLoadingResult](./resourceloadingresult/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [MarginsAreaUsageModes](./marginsareausagemodes/) | Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de los márgenes. |
| [PageSizeAdjustmentModes](./pagesizeadjustmentmodes/) | ¡ATENCIÓN! La funcionalidad está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Obtiene la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando **true** |

, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia desactivan la incrustación para esa fuente. Por defecto **false**

. |
| [get_LoadFormat](./get_loadformat/)() const | Representa el formato de archivo que describe [LoadOptions](./). |
| [get_WarningHandler](./get_warninghandler/)() const | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../returnaction/) que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar. |
| [LoadOptions](./loadoptions/)() |  |
|  | [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando **true** |

, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia desactivan la incrustación para esa fuente. Por defecto **false**

. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../returnaction/) que especifica Continue o Abort. Continue es la acción predeterminada y la operación Load continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Load debe cesar. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ResourceLoadingStrategy](./resourceloadingstrategy/) | A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados desde algún lugar. Por ejemplo, durante el uso de [Aspose.Pdf](../) en la nube el acceso directo a los archivos referenciados es imposible, y se debe utilizar código personalizado colocado en un método especial. Este delegado define la firma de dicho método personalizado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
