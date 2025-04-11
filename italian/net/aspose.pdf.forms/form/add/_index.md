---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Aggiunge un campo al modulo
type: docs
weight: 190
url: /it/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Aggiunge un campo al modulo.

```csharp
public void Add(Field field, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| field | Field | Campo che deve essere aggiunto. |
| pageNumber | Int32 | Indice della pagina in cui verrà posizionato il campo aggiunto. |

### Vedi Anche

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Aggiunge un campo al modulo.

```csharp
public void Add(Field field)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| field | Field | Campo che deve essere aggiunto. |

### Vedi Anche

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Aggiunge un nuovo campo al modulo; Se questo campo è già posizionato su un altro modulo o su questo modulo, verrà creata una copia del campo.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| field | Field | Nome del campo. |
| partialName | String | Nome del campo sul modulo. |
| pageNumber | Int32 | Numero della pagina in cui verrà aggiunto il campo. |

### Valore di Ritorno

Campo aggiunto restituito. Se è stata creata una copia del campo, verrà restituita.

### Vedi Anche

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)