---
title: "CosPdfDictionary.Remove"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод CosPdfDictionary. Удаляет элемент с указанным ключом из CosPdfDictionary"
type: docs
weight: 150
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Удаляет элемент с указанным ключом из [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Ключ элемента, который нужно удалить. |

### Возвращаемое значение

True, если элемент успешно удалён; в противном случае — false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не редактируемый

### См. также

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Удаляет первое вхождение конкретного объекта из [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Объект, который нужно удалить из [`CosPdfDictionary`](../). |

### Возвращаемое значение

true, если элемент был успешно удалён из [`CosPdfDictionary`](../); иначе false. Этот метод также возвращает false, если элемент не найден в оригинальном [`CosPdfDictionary`](../).

### См. также

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


