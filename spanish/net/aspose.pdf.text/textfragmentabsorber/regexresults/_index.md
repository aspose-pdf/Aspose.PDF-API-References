---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextFragmentAbsorber. Obtiene un diccionario de ocurrencias de búsqueda que se presentan con la clase System.Text.RegularExpressions.Regex como clave y TextFragment como valor
type: docs
weight: 60
url: /es/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## Propiedad TextFragmentAbsorber.RegexResults

Obtiene un diccionario de ocurrencias de búsqueda que se presentan con la clase System.Text.RegularExpressions.Regex como clave y [`TextFragment`](../../textfragment/) como valor.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## Ejemplos

El ejemplo demuestra cómo encontrar texto con un array de expresiones regulares en la primera página del documento PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### Véase también

* clase [TextFragmentCollection](../../textfragmentcollection/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)