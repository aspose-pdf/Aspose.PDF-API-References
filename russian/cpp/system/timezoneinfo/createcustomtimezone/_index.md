---
title: "System::TimeZoneInfo::CreateCustomTimeZone метод"
linktitle: "CreateCustomTimeZone"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TimeZoneInfo::CreateCustomTimeZone метод. Создаёт пользовательский часовой пояс в C++."
type: docs
weight: 700
url: /ru/cpp/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


Создаёт пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const String\& | Идентификатор часового пояса. |
| base_utc_offset | TimeSpan | Временной интервал между стандартным временем текущего часового пояса и UTC. |
| display_name | const String\& | Отображаемое имя. |
| standard_display_name | const String\& | Имя стандартного времени. |

### ReturnValue

Новый часовой пояс.

## См. также

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


Создаёт пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const String\& | Идентификатор часового пояса. |
| base_utc_offset | TimeSpan | Временной интервал между стандартным временем текущего часового пояса и UTC. |
| display_name | const String\& | Отображаемое имя. |
| standard_display_name | const String\& | Имя стандартного времени. |
| daylight_display_name | const String\& | Имя летнего времени. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) правил корректировки. |

### ReturnValue

Новый часовой пояс.

## См. также

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


Создаёт пользовательский часовой пояс.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| id | const String\& | Идентификатор часового пояса. |
| base_utc_offset | TimeSpan | Временной интервал между стандартным временем текущего часового пояса и UTC. |
| display_name | const String\& | Отображаемое имя. |
| standard_display_name | const String\& | Имя стандартного времени. |
| daylight_display_name | const String\& | Имя летнего времени. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) правил корректировки. |
| disable_daylight_saving_time | bool | True чтобы удалить любую информацию о летнем времени, присутствующую в adjustment_rules. |

### ReturnValue

Новый часовой пояс.

## См. также

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
