---
title: "Document.IgnoreCorruptedObjects"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Document property. Получает или задает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены, при значении флага false. пример dest.Pages.Addsrc.Pages. Если флаг установлен в true, повреждённые объекты заменяются пустыми значениями. По умолчанию true"
type: docs
weight: 290
url: /ru/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

Получает флаг игнорирования ошибок в исходных файлах. Когда страницы из исходного документа копируются в целевой документ, процесс копирования останавливается с исключением, если некоторые объекты в исходных файлах повреждены, при условии, что этот флаг установлен в false. пример: dest.Pages.Add(src.Pages); Если этот флаг установлен в true, повреждённые объекты будут заменены пустыми значениями. По умолчанию: true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


