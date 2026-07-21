---
title: "Aspose::Pdf::SaveOptions class"
linktitle: "SaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::SaveOptions. El tipo SaveOptions mantiene un nivel de abstracción sobre opciones de guardado individuales en C++."
type: docs
weight: 17200
url: /es/cpp/aspose.pdf/saveoptions/
---
## SaveOptions class


[SaveOptions](./) type hold level of abstraction on individual save options.

```cpp
class SaveOptions : public virtual System::Object
```

## Nested classes

* Class [BorderInfo](./borderinfo/)
* Class [BorderPartStyle](./borderpartstyle/)
* Class [MarginInfo](./margininfo/)
* Class [MarginPartStyle](./marginpartstyle/)
* Class [ResourceSavingInfo](./resourcesavinginfo/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [HtmlBorderLineType](./htmlborderlinetype/) | Representa tipos de línea que pueden usarse en el documento resultante para dibujar bordes u otras líneas. |
| [NodeLevelResourceType](./nodelevelresourcetype/) | Enumera los tipos posibles de recursos externos guardados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_CacheGlyphs](./get_cacheglyphs/)() const | Obtiene un valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria. |
| [get_CloseResponse](./get_closeresponse/)() const | Obtiene un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [get_SaveFormat](./get_saveformat/)() const | Formato de guardado de datos. |
| [get_WarningHandler](./get_warninghandler/)() const | Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../returnaction/) que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación Save continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Save debe detenerse. |
| [SaveOptions](./saveoptions/)() |  |
| [set_CacheGlyphs](./set_cacheglyphs/)(bool) | Establece un valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria. |
| [set_CloseResponse](./set_closeresponse/)(bool) | Establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento enum [ReturnAction](../returnaction/) que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación Save continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Save debe detenerse. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
