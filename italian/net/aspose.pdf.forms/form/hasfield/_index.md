---
title: "Form.HasField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Verifica se il modulo ha già il campo specificato."
type: docs
weight: 300
url: /it/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Verifica se il modulo ha già il campo specificato.

```csharp
public bool HasField(Field field)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| campo | Campo | Campo da controllare. |

### Valore di ritorno

`true` se il nome del campo specificato è stato aggiunto al Form; altrimenti, `false`.

### Vedi anche

* class [Field](../../field/)
* class [Form](../)
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

### Valore di ritorno

`true` se il nome del campo specificato è stato aggiunto al Form; altrimenti, `false`.

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determina se il campo con il nome specificato è già stato aggiunto al modulo, con la possibilità di esaminare la gerarchia dei campi figli.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) o [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo. |
| searchChildren | Boolean | Quando impostato a `true` l'intera gerarchia dei campi del modulo verrà cercata per il *fieldName* richiesto (nota che in questo caso il [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) del campo richiesto dovrebbe essere passato come *fieldName*). |

### Valore di ritorno

`true` se il nome del campo specificato è stato aggiunto al Form; altrimenti, `false`.

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


