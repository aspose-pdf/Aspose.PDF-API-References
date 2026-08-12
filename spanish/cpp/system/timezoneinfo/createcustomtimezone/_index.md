---
title: "System::TimeZoneInfo::CreateCustomTimeZone método"
linktitle: "CreateCustomTimeZone"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TimeZoneInfo::CreateCustomTimeZone method. Crea una zona horaria personalizada en C++."
type: docs
weight: 700
url: /es/cpp/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const String\& | Identificador de zona horaria. |
| base_utc_offset | TimeSpan | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const String\& | Nombre para mostrar. |
| standard_display_name | const String\& | Nombre de hora estándar. |

### ReturnValue

Nueva zona horaria.

## Ver también

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const String\& | Identificador de zona horaria. |
| base_utc_offset | TimeSpan | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const String\& | Nombre para mostrar. |
| standard_display_name | const String\& | Nombre de hora estándar. |
| daylight_display_name | const String\& | Nombre de horario de verano. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) de reglas de ajuste. |

### ReturnValue

Nueva zona horaria.

## Ver también

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


Crea una zona horaria personalizada.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | const String\& | Identificador de zona horaria. |
| base_utc_offset | TimeSpan | Intervalo de tiempo entre la hora estándar de la zona horaria actual y la hora UTC. |
| display_name | const String\& | Nombre para mostrar. |
| standard_display_name | const String\& | Nombre de hora estándar. |
| daylight_display_name | const String\& | Nombre de horario de verano. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) de reglas de ajuste. |
| disable_daylight_saving_time | bool | True para descartar cualquier información de horario de verano presente en adjustment_rules. |

### ReturnValue

Nueva zona horaria.

## Ver también

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
