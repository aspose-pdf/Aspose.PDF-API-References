---
title: "PageCollection"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Коллекция страниц PDF‑документа."
type: docs
weight: 1100
url: /ru/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

Коллекция страниц PDF‑документа.

Тип PageCollection раскрывает следующие члены:
## Свойства
| Имя | Описание |
| :- | :- |
| is_synchronized | Возвращает true, если объект синхронизирован. |
| sync_root | Получает объект синхронизации коллекции. |
## Indexer
| Имя | Описание |
| :- | :- |
| [index] | Получает страницу по индексу. |
## Методы
| Имя | Описание |
| :- | :- |
| add(entity) | Добавляет страницу в коллекцию. |
| add() | Добавляет страницу в коллекцию. |
| add(pages) | Добавляет в коллекцию все страницы из списка. |
| add(pages) | Добавляет в коллекцию все страницы из массива. |
| delete(index) | Удаляет указанную страницу. |
| delete() | Удаляет указанную страницу. |
| delete(pages) | Удаляет страницы, номера которых указаны в массиве. |
| accept(visitor) | Принимает объект‑посетитель [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/), который предоставляет функциональность для работы с аннотациями. |
| accept(visitor) | Принимает объект‑посетитель [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/), который предоставляет функциональность для работы с объектами размещения изображений. |
| accept(visitor) | Принимает объект‑посетитель [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| accept(visitor) | Принимает объект‑посетитель [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| insert(page_number) | Вставляет пустую страницу в коллекцию в указанной позиции. |
| insert(page_number, entity) | Вставляет пустую страницу в коллекцию в указанной позиции. |
| insert(page_number, pages) | Вставляет страницы из коллекции в документ. |
| insert(page_number, pages) | Вставляет страницы из массива в документ. |
| index_of(entity) | Возвращает индекс указанной страницы. |
| flatten() | Удаляет все поля, расположенные на страницах, и вместо них размещает их значения. |
| free_memory() | Очищает кэшированные данные |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

