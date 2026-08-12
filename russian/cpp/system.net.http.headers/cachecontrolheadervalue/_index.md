---
title: "System::Net::Http::Headers::CacheControlHeaderValue класс"
linktitle: "CacheControlHeaderValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::Headers::CacheControlHeaderValue. Представляет значение заголовка ''Cache-Control''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue class


Представляет значение заголовка 'Cache-Control'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Создаёт новый экземпляр. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| [get_Extensions](./get_extensions/)() | Возвращает коллекцию токенов cache-extension. |
| [get_MaxAge](./get_maxage/)() | Получает значение максимального возраста в секундах, определяющее период, в течение которого клиент будет принимать ответ. |
| [get_MaxStale](./get_maxstale/)() | Получает значение, определяющее, будет ли клиент принимать просроченные ответы. |
| [get_MaxStaleLimit](./get_maxstalelimit/)() | Получает значение в секундах, определяющее период, в течение которого клиент будет принимать просроченные ответы. |
| [get_MinFresh](./get_minfresh/)() | Получает значение, определяющее срок актуальности. |
| [get_MustRevalidate](./get_mustrevalidate/)() | Получает значение, определяющее, требует ли сервер повторной проверки кэш‑записи, когда она становится устаревшей. |
| [get_NoCache](./get_nocache/)() | Информация RTTI. |
| [get_NoCacheHeaders](./get_nocacheheaders/)() | Получает коллекцию имён полей в директиве 'no-cache' заголовка 'Cache-Control'. |
| [get_NoStore](./get_nostore/)() | Получает значение, определяющее, не должен ли кэш хранить любую часть HTTP‑запроса или ответа. |
| [get_NoTransform](./get_notransform/)() | Получает значение, определяющее, не должен ли кэш или прокси изменять любую часть тела сущности. |
| [get_OnlyIfCached](./get_onlyifcached/)() | Получает значение, определяющее, должен ли клиент использовать только кэшированные записи. |
| [get_Private](./get_private/)() | Получает значение, определяющее, предназначено ли сообщение HTTP‑ответа или его часть для одного пользователя и не должно кэшироваться совместным кэшем. |
| [get_PrivateHeaders](./get_privateheaders/)() | Получает коллекцию имён полей в директиве 'private' заголовка 'Cache-Control'. |
| [get_ProxyRevalidate](./get_proxyrevalidate/)() | Получает значение, определяющее, требует ли сервер повторной проверки кэш‑записи, когда она становится устаревшей для совместных кэшей пользовательских агентов. |
| [get_Public](./get_public/)() | Получает значение, определяющее, может ли HTTP‑ответ кэшироваться любым кэшем. |
| [get_SharedMaxAge](./get_sharedmaxage/)() | Получает значение совместного максимального возраста в секундах, которое переопределяет директиву 'max-age' в заголовке 'Cache-Control' или заголовке 'Expires' для совместного кэша. |
| static [GetCacheControlLength](./getcachecontrollength/)(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [CacheControlHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [Parse](./parse/)(String) | Преобразует переданную строку в экземпляр класса [CacheControlHeaderValue](./). |
| [set_MaxAge](./set_maxage/)(Nullable\<TimeSpan\>) | Устанавливает значение максимального возраста в секундах, определяющее период, в течение которого клиент будет принимать ответ. |
| [set_MaxStale](./set_maxstale/)(bool) | Устанавливает значение, определяющее, будет ли клиент принимать просроченные ответы. |
| [set_MaxStaleLimit](./set_maxstalelimit/)(Nullable\<TimeSpan\>) | Устанавливает значение в секундах, определяющее период, в течение которого клиент будет принимать просроченные ответы. |
| [set_MinFresh](./set_minfresh/)(Nullable\<TimeSpan\>) | Устанавливает значение, определяющее срок актуальности. |
| [set_MustRevalidate](./set_mustrevalidate/)(bool) | Устанавливает значение, определяющее, требует ли сервер повторной проверки кэш‑записи, когда она становится устаревшей. |
| [set_NoCache](./set_nocache/)(bool) | Устанавливает значение, определяющее, будет ли клиент принимать кэшированный ответ. |
| [set_NoStore](./set_nostore/)(bool) | Устанавливает значение, определяющее, должен ли кэш не сохранять любую часть HTTP‑запроса или ответа. |
| [set_NoTransform](./set_notransform/)(bool) | Устанавливает значение, определяющее, должен ли кэш или прокси не изменять любую часть тела сущности. |
| [set_OnlyIfCached](./set_onlyifcached/)(bool) | Устанавливает значение, определяющее, должен ли клиент использовать только кэшированные записи. |
| [set_Private](./set_private/)(bool) | Устанавливает значение, определяющее, предназначено ли сообщение HTTP‑ответа или его часть для одного пользователя и не должно ли оно кэшироваться совместным кэшем. |
| [set_ProxyRevalidate](./set_proxyrevalidate/)(bool) | Устанавливает значение, определяющее, требует ли сервер повторной проверки кэш‑записи, когда она становится устаревшей для совместных кэшей пользовательских агентов. |
| [set_Public](./set_public/)(bool) | Устанавливает значение, определяющее, может ли HTTP‑ответ кэшироваться каким-либо кэшем. |
| [set_SharedMaxAge](./set_sharedmaxage/)(Nullable\<TimeSpan\>) | Устанавливает общее максимальное значение возраста в секундах, которое переопределяет директиву 'max-age' в заголовке 'Cache-Control' или заголовке 'Expires' для совместного кэша. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<CacheControlHeaderValue\>\&) | Пытается преобразовать переданную строку в экземпляр класса [CacheControlHeaderValue](./). |
## См. также

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
