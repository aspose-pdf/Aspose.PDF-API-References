---
title: "System::TimeZoneInfo::CreateCustomTimeZone metod"
linktitle: "CreateCustomTimeZone"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZoneInfo::CreateCustomTimeZone metod. Skapar en anpassad tidszon i C++."
type: docs
weight: 700
url: /sv/cpp/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const String\& | Tidszonsidentifierare. |
| base_utc_offset | TimeSpan | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const String\& | Visningsnamn. |
| standard_display_name | const String\& | Standardtidens namn. |

### ReturnValue

Ny tidszon.

## Se även

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const String\& | Tidszonsidentifierare. |
| base_utc_offset | TimeSpan | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const String\& | Visningsnamn. |
| standard_display_name | const String\& | Standardtidens namn. |
| daylight_display_name | const String\& | Sommartidsnamn. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) av justeringsregler. |

### ReturnValue

Ny tidszon.

## Se även

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const String\& | Tidszonsidentifierare. |
| base_utc_offset | TimeSpan | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const String\& | Visningsnamn. |
| standard_display_name | const String\& | Standardtidens namn. |
| daylight_display_name | const String\& | Sommartidsnamn. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) av justeringsregler. |
| disable_daylight_saving_time | bool | Sant för att ta bort all sommartidsinformation som finns i adjustment_rules. |

### ReturnValue

Ny tidszon.

## Se även

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
