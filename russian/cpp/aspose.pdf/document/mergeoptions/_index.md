---
title: "Aspose::Pdf::Document::MergeOptions class"
linktitle: "MergeOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document::MergeOptions class. Представляет параметры для методов Merge в C++."
type: docs
weight: 12700
url: /ru/cpp/aspose.pdf/document/mergeoptions/
---
## MergeOptions class


Представляет параметры для методов Merge.

```cpp
class MergeOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_ConcatenationPacketSize](./get_concatenationpacketsize/)() const | Количество документов, объединённых до того, как было выполнено новое инкрементное обновление во время конкатенации, когда UseDiskBuffer установлен в true. Значение по умолчанию — 4. |
| [get_IsNeedPageTreeBalance](./get_isneedpagetreebalance/)() const | Получает и задает требование балансировки дерева страниц. Весь дерево страниц в результирующем документе будет перебалансировано. Это создаёт сбалансированное дерево страниц для ускорения доступа к страницам. |
| [get_MaximumNodesInLevel](./get_maximumnodesinlevel/)() const | Получает и задает максимальное количество узлов на уровне дерева страниц. По умолчанию — 10. |
| [get_UseDiskBuffer](./get_usediskbuffer/)() const | Если эта опция используется, то целевой документ будет периодически сохраняться на диск, а дальнейшая конкатенация будет применяться к нему как инкрементные обновления. Значение по умолчанию — **false**. |
| [MergeOptions](./mergeoptions/)() |  |
| [set_ConcatenationPacketSize](./set_concatenationpacketsize/)(int32_t) | Количество документов, объединённых до того, как было выполнено новое инкрементное обновление во время конкатенации, когда UseDiskBuffer установлен в true. Значение по умолчанию — 4. |
| [set_IsNeedPageTreeBalance](./set_isneedpagetreebalance/)(bool) | Получает и задает требование балансировки дерева страниц. Весь дерево страниц в результирующем документе будет перебалансировано. Это создаёт сбалансированное дерево страниц для ускорения доступа к страницам. |
| [set_MaximumNodesInLevel](./set_maximumnodesinlevel/)(uint8_t) | Получает и задает максимальное количество узлов на уровне дерева страниц. По умолчанию — 10. |
| [set_UseDiskBuffer](./set_usediskbuffer/)(bool) | Если эта опция используется, то целевой документ будет периодически сохраняться на диск, а дальнейшая конкатенация будет применяться к нему как инкрементные обновления. Значение по умолчанию — **false**. |
## См. также

* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
