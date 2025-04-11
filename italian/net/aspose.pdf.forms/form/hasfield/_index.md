---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Controlla se il modulo ha già il campo specificato
type: docs
weight: 280
url: /it/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Controlla se il modulo ha già il campo specificato.

```csharp
public bool HasField(Field field)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| field | Field | Campo da controllare. |

### Valore di Ritorno

`true` se il nome del campo specificato è stato aggiunto al modulo; altrimenti, `false`.

### Vedi Anche

* classe [Field](../../field/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Determina se il campo con il nome specificato è già stato aggiunto al modulo.

```csharp
public bool HasField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo. |

### Valore di Ritorno

`true` se il nome del campo specificato è stato aggiunto al modulo; altrimenti, `false`.

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determina se il campo con il nome specificato è già stato aggiunto al modulo, con la possibilità di cercare nella gerarchia dei campi figli.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo. |
| searchChildren | Boolean | Quando impostato su `true`, verrà cercata l'intera gerarchia dei campi del modulo per il *fieldName* richiesto (nota che in questo caso il [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo richiesto deve essere passato come *fieldName*). |

### Valore di Ritorno

`true` se il nome del campo specificato è stato aggiunto al modulo; altrimenti, `false`.

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)