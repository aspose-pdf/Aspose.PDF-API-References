---
title: "Form.Add"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Aggiunge un campo al modulo"
type: docs
weight: 210
url: /it/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Aggiunge un campo al modulo.

```csharp
public void Add(Field field, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| campo | Campo | Campo che deve essere aggiunto. |
| pageNumber | Int32 | Indice della pagina in cui il campo aggiunto sarà posizionato. |

### Vedi anche

* class [Field](../../field/)
* class [Form](../)
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
| campo | Campo | Campo che deve essere aggiunto. |

### Vedi anche

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Aggiunge un nuovo campo al modulo; se questo campo è già posizionato su un altro modulo o su questo, viene creata una copia del campo.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| campo | Campo | Nome del campo. |
| partialName | String | Nome del campo nel modulo. |
| pageNumber | Int32 | Numero di pagina dove verrà aggiunto il campo. |

### Valore di ritorno

Campo aggiunto restituito. Se è stata creata una copia del campo, verrà restituita.

### Vedi anche

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


