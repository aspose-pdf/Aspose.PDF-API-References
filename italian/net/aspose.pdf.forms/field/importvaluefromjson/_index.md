---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Metodo del campo. Importa dati nei campi specificati da un flusso JSON basato su una corrispondenza esatta dei nomi completi dei campi
type: docs
weight: 210
url: /it/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importa dati nei campi specificati da un flusso JSON, basato su una corrispondenza esatta dei nomi completi dei campi.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputJsonStream | Stream | Il flusso JSON di input contenente i dati del campo da importare nel campo. |

### Valore di ritorno

Vero se il campo è stato trovato nel flusso JSON; altrimenti - falso

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Vedi Anche

* classe [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importa dati nel campo specificato da un flusso JSON, utilizzando il nome completo specificato nella variabile 'fieldFullNameInJSON' per la corrispondenza.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputJsonStream | Stream | Il flusso JSON di input contenente i dati del campo da importare nel campo. |
| fieldFullNameInJSON | String | Il nome dei dati all'interno del flusso JSON per la corrispondenza. Se i dati all'interno del flusso JSON hanno una struttura annidata, il nome completo deve essere specificato con tutti gli elementi genitori e figli separati da '.' |

### Valore di ritorno

Vero se il campo è stato trovato nel file json; altrimenti - falso

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Vedi Anche

* classe [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)