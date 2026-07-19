---
title: "System::Security::SecureString класс"
linktitle: "SecureString"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::SecureString. Secure string, представляет текст, который должен оставаться конфиденциальным. Этот класс DON''T ENCRYPTING внутренние данные. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security/securestring/
---
## SecureString class


Secure string, представляет текст, который должен оставаться конфиденциальным. Этот класс DON'T ENCRYPTING внутренние данные. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SecureString : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [AppendChar](./appendchar/)(char16_t) | Добавляет символ в конец строки. |
| [Clear](./clear/)() | Удаляет все символы из текущей защищённой строки. |
| [Copy](./copy/)() const | Создаёт копию этой защищённой строки. |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим объектом. |
| [get_Length](./get_length/)() const | Возвращает количество символов в этой защищённой строке. |
| [InsertAt](./insertat/)(int32_t, char16_t) | Вставляет символ в указанную позицию. |
| [IsReadOnly](./isreadonly/)() const | Возвращает флаг, указывающий, помечен ли этот объект как только для чтения. |
| [MakeReadOnly](./makereadonly/)() | Делает эту защищённую строку только для чтения. |
| [operator=](./operator=/)(const SecureString\&) |  |
| [RemoveAt](./removeat/)(int32_t) | Удаляет символ в указанной позиции. |
| [SecureString](./securestring/)() | Информация RTTI. |
| [SecureString](./securestring/)(const char16_t *, int32_t) | Конструктор. |
| [SecureString](./securestring/)(const SecureString\&) |  |
| [SetAt](./setat/)(int32_t, char16_t) | Заменяет существующий символ в указанной позиции. |
| [ToUnsecureString](./tounsecurestring/)() const | Копирует содержимое этой защищённой строки в небезопасный объект [String](../../system/string/). Используйте с осторожностью. |
| [~SecureString](./~securestring/)() | Деструктор. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
