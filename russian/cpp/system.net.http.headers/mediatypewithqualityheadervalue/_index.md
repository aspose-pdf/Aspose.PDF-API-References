---
title: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue класс"
linktitle: "MediaTypeWithQualityHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue класс. Представляет MIME‑тип с дополнительным коэффициентом качества в значении заголовка ''Content-Type''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue class


Представляет MIME‑тип с дополнительным коэффициентом качества в значении заголовка 'Content-Type'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Quality](./get_quality/)() | Информация RTTI. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Создаёт новый экземпляр. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String) | Создаёт новый экземпляр. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String, double) | Создаёт новый экземпляр. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [MediaTypeWithQualityHeaderValue](./). |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Устанавливает значение качества. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeWithQualityHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [MediaTypeWithQualityHeaderValue](./). |
## См. также

* Class [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
