---
title: PdfFileSignature.GetSignatureNames
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Obtiene los nombres de todas las firmas no vacías
type: docs
weight: 210
url: /es/net/aspose.pdf.facades/pdffilesignature/getsignaturenames/
---
## Método PdfFileSignature.GetSignatureNames

Obtiene los nombres de todas las firmas no vacías.

```csharp
public IList<SignatureName> GetSignatureNames(bool onlyActive = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onlyActive | Booleano | si es verdadero, devuelve solo las firmas activas; de lo contrario, devuelve todas las firmas. |

### Valor de Retorno

Devuelve un IList&lt;SignatureName&gt;.

## Ejemplos

```csharp
[C#]
string inFile=TestPath + "example1.pdf";
PdfFileSignature pdfSign=new PdfFileSignature();
pdfSign.BindPdf(inFile); 
var names=pdfSign.GetSignatureNames();
or(int i=0;i<names.Count;i++)

 Console.WriteLine("signature name:" + names[i]);
 Console.WriteLine("coverswholedocument:" + pdfSign.CoversWholeDocument(names[i]));
 Console.WriteLine("revision:" + pdfSign.GetRevision(names[i]));	
 Console.WriteLine("verifysigned:" + pdfSign.VerifySignature(names[i]));
 Console.WriteLine("reason:" + pdfSign.GetReason(names[i]));
 Console.WriteLine("location:" + pdfSign.GetLocation(names[i]));
 Console.WriteLine("datatime:" + pdfSign.GetDateTime(names[i]));		
}
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision());
[Visual Basic]
Dim pdfSign as PdfFileSignature =new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names=pdfSign.GetSignNames()
For i=0 To names.Count

	Console.WriteLine("signature name:" + (SignatureName)names[i])
	Console.WriteLine("coverswholedocument:" + pdfSign.IsCoversWholeDocument((string)names[i]))
	Console.WriteLine("revision:" + pdfSign.GetRevision((SignatureName)names[i]))	
	Console.WriteLine("verifysigned:" + pdfSign.VerifySignature((SignatureName)names[i]))
	Console.WriteLine("reason:" + pdfSign.GetReason((SignatureName)names[i]))
	Console.WriteLine("location:" + pdfSign.GetLocation((SignatureName)names[i]))
	Console.WriteLine("datatime:" + pdfSign.GetDateTime((SignatureName)names[i]))	
Next i
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision())
```

### Ver También

* clase [SignatureName](../../signaturename/)
* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)