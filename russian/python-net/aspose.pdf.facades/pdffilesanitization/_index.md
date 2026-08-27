---
title: "PdfFileSanitization"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет API очистки и восстановления.<br/>            Используйте его, если вы не можете создавать/открывать документы иным способом."
type: docs
weight: 290
url: /ru/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Представляет API очистки и восстановления.<br/>            Используйте его, если вы не можете создавать/открывать документы иным способом.

Тип PdfFileSanitization раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileSanitization() | Инициализирует новый экземпляр класса PdfFileSanitization |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| log | После сохранения файла вы можете проверить, что было сделано с файлом. |
| use_trim_top | Позволяет удалить данные перед данными pdf. |
| use_trim_bottom | Позволяет удалить данные после данных pdf |
| use_rebuild_xref_and_trailer | Позволяет сгенерировать новый xref и трейлер для документа. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(input_file) | Привязывает PDF‑файл для очистки. |
| bind_pdf(input_stream) | Привязывает PDF‑поток для очистки. |
| bind_pdf(src_doc) | Инициализирует фасад. |
| save(output_file) | Сохраняет полученный PDF в файл. |
| save(output_stream) | Сохраняет полученный PDF в поток. |
| close() | Закрывает фасад. |
| recover() | Восстанавливает документ.<br/>            Используйте свойства для настройки. |
| trim_top() | Удаляет данные перед %PDF. |
| trim_bottom() | Удаляет данные после последнего %%EOF. |
| rebuild_xref_and_trailer() | Удаляет старый xref с трейлером и создает новый xref с трейлером. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

