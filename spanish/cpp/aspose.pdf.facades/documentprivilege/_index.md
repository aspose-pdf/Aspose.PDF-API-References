---
title: "Aspose::Pdf::Facades::DocumentPrivilege class"
linktitle: "DocumentPrivilege"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::DocumentPrivilege class. Representa los privilegios para acceder al archivo Pdf. Consulte a PdfFileSecurity. Hay 4 formas de usar esta clase: 1. Usar privilegio predefinido directamente. 2. Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3. Basado en un privilegio predefinido y cambiar alguna combinación específica de permisos de Adobe Professional. 4. Mezcla la forma 2 y la forma 3 en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class


Representa los privilegios para acceder al archivo [Pdf](../../aspose.pdf/). Consulte a [PdfFileSecurity](../pdffilesecurity/). Hay 4 formas de usar esta clase: 1. Usar privilegio predefinido directamente. 2. Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3. Basado en un privilegio predefinido y cambiar alguna combinación específica de permisos de Adobe Professional. 4. Mezcla la forma 2 y la forma 3.

```cpp
class DocumentPrivilege : public System::IComparable<System::SharedPtr<System::Object>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<System::Object\>) override | Compara dos objetos [DocumentPrivilege](./). |
| static [get_AllowAll](./get_allowall/)() | Todo permitido. |
| [get_AllowAssembly](./get_allowassembly/)() | Establece el permiso que permite el ensamblado o no. true permite y false está prohibido. |
| [get_AllowCopy](./get_allowcopy/)() | Establece el permiso que permite la copia o no. true permite y false está prohibido. |
| [get_AllowDegradedPrinting](./get_allowdegradedprinting/)() | Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. |
| [get_AllowFillIn](./get_allowfillin/)() | Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido. |
| [get_AllowModifyAnnotations](./get_allowmodifyannotations/)() | Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido. |
| [get_AllowModifyContents](./get_allowmodifycontents/)() | Establece el permiso que permite modificar el contenido o no. true permite y false está prohibido. |
| [get_AllowPrint](./get_allowprint/)() | Establece el permiso que permite imprimir o no. true permite y false está prohibido. |
| [get_AllowScreenReaders](./get_allowscreenreaders/)() | Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido. |
| static [get_Assembly](./get_assembly/)() | Permite ensamblar el archivo. |
| [get_ChangeAllowLevel](./get_changeallowlevel/)() | Obtiene y establece el nivel de cambio del privilegio del documento. Igual que la configuración 'Changes Allowed' de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier cosa excepto extraer páginas. |
| static [get_Copy](./get_copy/)() | Permite copiar el archivo. |
| [get_CopyAllowLevel](./get_copyallowlevel/)() | Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectores de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. |
| static [get_DegradedPrinting](./get_degradedprinting/)() | Permite impresión degradada. |
| static [get_FillIn](./get_fillin/)() | Permite rellenar formularios en el archivo. |
| static [get_ForbidAll](./get_forbidall/)() | Todo prohibido. |
| static [get_ModifyAnnotations](./get_modifyannotations/)() | Permite modificar anotaciones del archivo. |
| static [get_ModifyContents](./get_modifycontents/)() | Permite modificar el archivo. |
| static [get_Print](./get_print/)() | Permite imprimir el archivo. |
| [get_PrintAllowLevel](./get_printallowlevel/)() | Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración 'Printing Allowed' de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. |
| static [get_ScreenReaders](./get_screenreaders/)() | Permite solo la lectura en pantalla. |
| [set_AllowAssembly](./set_allowassembly/)(bool) | Establece el permiso que permite el ensamblado o no. true permite y false está prohibido. |
| [set_AllowCopy](./set_allowcopy/)(bool) | Establece el permiso que permite la copia o no. true permite y false está prohibido. |
| [set_AllowDegradedPrinting](./set_allowdegradedprinting/)(bool) | Establece el permiso que permite la impresión degradada o no. true permite y false está prohibido. |
| [set_AllowFillIn](./set_allowfillin/)(bool) | Establece el permiso que permite rellenar formularios o no. true permite y false está prohibido. |
| [set_AllowModifyAnnotations](./set_allowmodifyannotations/)(bool) | Establece el permiso que permite modificar anotaciones o no. true permite y false está prohibido. |
| [set_AllowModifyContents](./set_allowmodifycontents/)(bool) | Establece el permiso que permite modificar el contenido o no. true permite y false está prohibido. |
| [set_AllowPrint](./set_allowprint/)(bool) | Establece el permiso que permite imprimir o no. true permite y false está prohibido. |
| [set_AllowScreenReaders](./set_allowscreenreaders/)(bool) | Establece el permiso que permite lectores de pantalla o no. true permite y false está prohibido. |
| [set_ChangeAllowLevel](./set_changeallowlevel/)(int32_t) | Obtiene y establece el nivel de cambio del privilegio del documento. Igual que la configuración 'Changes Allowed' de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar campos de firma existentes. 4: Cualquier cosa excepto extraer páginas. |
| [set_CopyAllowLevel](./set_copyallowlevel/)(int32_t) | Obtiene y establece el nivel de copia del privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos de lectores de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otro contenido. |
| [set_PrintAllowLevel](./set_printallowlevel/)(int32_t) | Obtiene y establece el nivel de impresión del privilegio del documento. Igual que la configuración 'Printing Allowed' de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 dpi). 2: Alta resolución. |
## Ver también

* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
