---
title: Visit
second_title: Aspose.PDF per .NET API Reference
description: Esegue la ricerca sulla pagina specificata.
type: docs
weight: 140
url: /it/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Esegue la ricerca sulla pagina specificata.

```csharp
public override void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | Oggetto pagina documento PDF. |

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituirlo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e finiscono con 'o' usando un'espressione regolare.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
absorber.Visit(doc.Pages[1]);

// Apri documento
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [Page](../../../aspose.pdf/page)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Esegue la ricerca sul documento specificato.

```csharp
public override void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto documento PDF. |

### Esempi

L'esempio mostra come trovare testo su un documento PDF e sostituire il testo di tutte le occorrenze di ricerca.

```csharp
// Modifica il testo di tutte le occorrenze di ricerca
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Modifica il testo di tutte le occorrenze di ricerca
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
absorber.Visit(doc);

// Apri documento
absorber.TextFragments[1].Text = "hi world";

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Esegue la ricerca sull'oggetto modulo specificato.

```csharp
public void Visit(XForm xForm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xForm | XForm | Oggetto modulo PDF. |

### Guarda anche

* class [XForm](../../../aspose.pdf/xform)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
