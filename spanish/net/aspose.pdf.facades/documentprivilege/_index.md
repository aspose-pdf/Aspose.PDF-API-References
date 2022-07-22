---
title: DocumentPrivilege
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa los privilegios para acceder al archivo PDF. Referirse aPdfFileSecurity./pdffilesecurity . Hay 4 formas de usar esta clase 1.Usar privilegios predefinidos directamente. 2.Basarse en un privilegio predefinido y cambiar algunos permisos específicos. 3.Basarse en un privilegio predefinido y cambiar alguna combinación de permisos específicos de Adobe Professional. 4.Mezcla way2 y way3.
type: docs
weight: 2240
url: /es/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Representa los privilegios para acceder al archivo PDF. Referirse a[`PdfFileSecurity`](../pdffilesecurity) . Hay 4 formas de usar esta clase: 1.Usar privilegios predefinidos directamente. 2.Basarse en un privilegio predefinido y cambiar algunos permisos específicos. 3.Basarse en un privilegio predefinido y cambiar alguna combinación de permisos específicos de Adobe Professional. 4.Mezcla way2 y way3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Todo permitido. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Permite ensamblar archivo. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Permite copiar archivo. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Permite impresión degradada. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Permite llenar formularios en archivo. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Todo Prohibido. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Permite modificar anotaciones del archivo. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Permite modificar archivo. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Permite imprimir archivo. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Permite leer solo en pantalla. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Establece el permiso que permite o no el montaje. verdadero está permitido y falso está prohibido. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Establece el permiso que permite copiar o no. verdadero está permitido y falso está prohibido. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Establece el permiso que permite o no la impresión degradada. verdadero está permitido y falso está prohibido. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Establece los permisos que permiten o no rellenar formularios. verdadero está permitido y falso está prohibido. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Establece el permiso que permite modificar o no las anotaciones. verdadero está permitido y falso está prohibido. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Establece los permisos que permiten modificar o no los contenidos. verdadero está permitido y falso está prohibido. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Establece el permiso que permite imprimir o no. verdadero está permitido y falso está prohibido. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Establece el permiso que permite o no los lectores de pantalla. verdadero está permitido y falso está prohibido. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Establece el nivel de cambio de privilegio del documento. Al igual que la configuración de Cambios permitidos de Adobe Professional. 0: Ninguno. 1: Insertar, eliminar y rotar páginas. 2: Rellenar campos de formulario y firmar campos de firma existentes. 3: Comentar, rellenar campos de formulario y firmar existentes campos de firma. 4: Cualquiera excepto páginas de extracción. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Establece el nivel de copia del privilegio del documento. Al igual que la configuración de permisos de Adobe Professional. 0: Ninguno. 1: Habilitar acceso de texto para dispositivos lectores de pantalla para personas con problemas de visión. 2: Habilitar copia de texto, imágenes y otro contenido. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Establece el nivel de impresión del privilegio del documento. Igual que la configuración de Impresión permitida de Adobe Professional. 0: Ninguno. 1: Baja resolución (150 ppp). 2: Alta resolución. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Compara dos[`DocumentPrivilege`](../documentprivilege) objetos.  El objeto con el que comparar. Un entero con signo que indica los valores relativos de esta instancia y valor. Menos que cero, esta instancia es menor que el valor. Cero esta instancia es igual al valor. Mayor que cero, esta instancia es mayor que el valor. |

### Ejemplos

```csharp
[C#]	
//Way1: Uso de privilegios predefinidos directamente.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Basado en un privilegio predefinido y cambia algunos permisos específicos.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: basado en un privilegio predefinido y cambia alguna combinación de permisos de Adobe Professional específica.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mezcla way2 y way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: usar privilegios predefinidos directamente.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Basado en un privilegio predefinido y cambiar algunos permisos específicos.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Basado en un privilegio predefinido y cambia alguna combinación específica de permisos de Adobe Professional.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mezcla way2 y way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Ver también

* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
