---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.DocumentPrivilege. Representa los privilegios para acceder a archivos Pdf. Consulte PdfFileSecurity. Hay 4 formas de usar esta clase: 1. Usando privilegios predefinidos directamente. 2. Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3. Basado en un privilegio predefinido y cambiar algunas combinaciones de permisos específicos de Adobe Professional. 4. Mezcla la forma 2 y la forma 3.
type: docs
weight: 4230
url: /es/net/aspose.pdf.facades/documentprivilege/
---
## Clase DocumentPrivilege

Representa los privilegios para acceder a archivos Pdf. Consulte [`PdfFileSecurity`](../pdffilesecurity/). Hay 4 formas de usar esta clase: 1. Usando privilegios predefinidos directamente. 2. Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3. Basado en un privilegio predefinido y cambiar algunas combinaciones de permisos específicos de Adobe Professional. 4. Mezcla la forma 2 y la forma 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Todo permitido. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Permite ensamblar el archivo. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Permite copiar el archivo. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Permite impresión degradada. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Permite llenar formularios en el archivo. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Todo prohibido. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Permite modificar anotaciones del archivo. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Permite modificar el archivo. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Permite imprimir el archivo. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Permite solo lectura en pantalla. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Establece el permiso que permite ensamblar o no. verdadero es permitir y falso es prohibir. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Establece el permiso que permite copiar o no. verdadero es permitir y falso es prohibir. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Establece el permiso que permite impresión degradada o no. verdadero es permitir y falso es prohibir. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Establece el permiso que permite llenar formularios o no. verdadero es permitir y falso es prohibir. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Establece el permiso que permite modificar anotaciones o no. verdadero es permitir y falso es prohibir. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Establece el permiso que permite modificar contenidos o no. verdadero es permitir y falso es prohibir. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Establece el permiso que permite imprimir o no. verdadero es permitir y falso es prohibir. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Establece el permiso que permite lectores de pantalla o no. verdadero es permitir y falso es prohibir. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Obtiene y establece el nivel de cambio de privilegio del documento. Igual que la configuración de Cambios Permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, Eliminar y Rotar páginas. 2: Llenar campos de formulario y firmar campos de firma existentes. 3: Comentar, llenar campos de formulario y firmar campos de firma existentes. 4: Cualquier cosa excepto extraer páginas. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Obtiene y establece el nivel de copia de privilegio del documento. Igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso al texto para dispositivos de lectura de pantalla para personas con discapacidad visual. 2: Habilitar la copia de texto, imágenes y otros contenidos. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Obtiene y establece el nivel de impresión de privilegio del documento. Igual que la configuración de Impresión Permitida de Adobe Professional. 0: Ninguno. 1: Baja Resolución (150 dpi). 2: Alta Resolución. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Compara dos objetos `DocumentPrivilege`. El objeto con el que comparar. Un entero firmado que indica los valores relativos de esta instancia y el valor. Menos que cero esta instancia es menor que el valor. Cero esta instancia es igual al valor. Mayor que cero esta instancia es mayor que el valor. |

## Ejemplos

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Ver También

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)