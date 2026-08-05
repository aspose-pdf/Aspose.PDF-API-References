---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет базовый класс для коллекции операторов."
type: docs
weight: 70
url: /ru/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Представляет базовый класс для коллекции операторов.

Тип BaseOperatorCollection раскрывает следующие члены:
## Свойства
| Имя | Описание |
| :- | :- |
| is_fast_text_extraction_mode | Указывает, ограничена ли коллекция быстрым извлечением текста |
## Indexer
| Имя | Описание |
| :- | :- |
| [index] | Получает оператор по его индексу. |
## Методы
| Имя | Описание |
| :- | :- |
| suppress_update() | Подавляет обновление данных содержимого.<br/>            Поток содержимого не обновляется, пока не будет вызвано ResumeUpdate. |
| resume_update() | Возобновляет обновление документа.<br/>            Обновляет поток содержимого, если есть ожидающие изменения. |
| insert(index, op) | Вставляет оператор в коллекцию. |
| cancel_update() | Отменяет последнее обновление.<br/>            Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

