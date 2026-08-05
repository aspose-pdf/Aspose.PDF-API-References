---
title: "PdfFileSignature"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для подписи pdf‑файла с помощью сертификата."
type: docs
weight: 310
url: /ru/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Представляет класс для подписи pdf‑файла с помощью сертификата.

Тип PdfFileSignature раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileSignature() | Конструктор класса PdfFileSignature. |
| PdfFileSignature(input_file) | Инициализирует новый экземпляр класса PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Инициализирует новый экземпляр класса PdfFileSignature |
| PdfFileSignature(document) | Инициализирует новый экземпляр класса PdfFileSignature |
| PdfFileSignature(document, output_file) | Инициализирует новый экземпляр класса PdfFileSignature |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| signature_appearance | Устанавливает или получает графическое отображение подписи. Значение свойства представляет имя файла изображения. |
| is_ltv_enabled | Получает флаг включения LTV. |
| is_certified | Получает флаг, определяющий, сертифицирован документ или нет. |
| signature_appearance_stream | Устанавливает или получает графическое отображение подписи. Значение свойства представляет поток изображения. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(input_file) | Привязывает PDF‑файл для редактирования. |
| bind_pdf(input_stream) | Привязывает поток PDF для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(output_file) | Сохраняет полученный PDF в файл. |
| save(output_stream) | Сохраняет полученный PDF в поток. |
| save() | Сохраняет полученный PDF в файл. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Создайте подпись в PDF‑документе. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Подпишите документ указанной типовой подписью. |
| sign(page, visible, annot_rect, sig) | Подпишите документ указанной типовой подписью. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Подпишите документ указанной типовой подписью. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Подпишите документ указанной типовой подписью. |
| sign(sig_name, sig) | Подпишите документ указанной типовой подписью. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Заверить документ подписью MDP.<br/>            Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| certify(sig_name, doc_mdp_signature) | Заверить документ подписью MDP.<br/>            Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| remove_signature(sign_name) | Удалить подпись по её имени. |
| remove_signature(sign_name, remove_field) | Удаляет подпись по её имени. |
| close() | Закрывает фасад. |
| get_access_permissions() | Возвращает значение прав доступа сертифицированного документа по типу подписи MDP. |
| get_sign_names(only_active) | Получает имена всех непустых подписей. |
| get_blank_sign_names() | Получает имена всех пустых полей подписи. |
| is_contain_signature() | Проверяет, имеет ли PDF цифровую подпись. |
| contains_signature() | Проверяет, имеет ли PDF цифровую подпись. |
| contains_usage_rights() | Проверяет, есть ли у pdf права использования, или нет. |
| is_covers_whole_document(sign_name) | Проверяет, покрывает ли подпись весь документ. |
| covers_whole_document(sign_name) | Проверяет, покрывает ли подпись весь документ. |
| get_revision(sign_name) | Получает ревизию подписи. |
| get_total_revision() | Получает общую ревизию. |
| remove_usage_rights() | Удаляет запись прав использования. |
| verify_signed(sign_name) | Проверяет действительность подписи. |
| get_signer_name(sign_name) | Получает имя лица или организации, подписывающих pdf‑документ. |
| get_date_time(sign_name) | Получает дату и время подписи. |
| get_reason(sign_name) | Получает причину подписи. |
| get_location(sign_name) | Получает местоположение подписи. |
| get_contact_info(sign_name) | Получает контактную информацию подписи. |
| verify_signature(sign_name) | Проверяет действительность подписи. |
| extract_image(sign_name) | Извлекает изображение подписи. |
| extract_certificate(sign_name) | Извлекает единственный X.509 сертификат подписи в виде потока. |
| set_certificate(pfx, pass) | Устанавливает файл сертификата и пароль для процедуры подписи. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

