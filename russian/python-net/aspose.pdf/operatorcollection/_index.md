---
title: "OperatorCollection"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Класс представляет коллекцию операторов"
type: docs
weight: 1010
url: /ru/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Класс представляет коллекцию операторов

Тип OperatorCollection раскрывает следующие члены:
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
| insert(index, op) | Вставляет оператор в коллекцию. |
| insert(at, ops) | Вставляет операторы в указанную позицию. |
| insert(at, ops) | Вставляет оператор в коллекцию. |
| delete(index) | Удаляет оператор из коллекции. |
| delete(ops) | Удаляет операторы из коллекции. |
| delete(list) | None |
| add(ops) | Добавляет операторы в конец операторов содержимого. |
| add(ops) | Добавляет новый оператор в коллекцию. |
| suppress_update() | Подавляет обновление данных содержимого.<br/>            Поток содержимого не обновляется, пока не будет вызвано ResumeUpdate. |
| resume_update() | Возобновляет обновление документа.<br/>            Обновляет поток содержимого, если есть ожидающие изменения. |
| cancel_update() | Отменяет последнее обновление.<br/>            Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого. |
| accept(visitor) | Принимает объект‑посетитель IOperatorSelector для обработки операторов. |
| replace(operators) | Заменить операторы в коллекции другими операторами. |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

