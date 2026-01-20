---
title: System::TimeZoneInfo::CreateCustomTimeZone method
linktitle: CreateCustomTimeZone
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::CreateCustomTimeZone method. Creates a custom time zone in C++.'
type: docs
weight: 700
url: /cpp/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| id | const String\& | Time zone identifier. |
| base_utc_offset | TimeSpan | Time interval between the current time zone's standard time and UTC time. |
| display_name | const String\& | Display name. |
| standard_display_name | const String\& | Standard time name. |

### ReturnValue

New time zone.

## See Also

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


| Parameter | Type | Description |
| --- | --- | --- |
| id | const String\& | Time zone identifier. |
| base_utc_offset | TimeSpan | Time interval between the current time zone's standard time and UTC time. |
| display_name | const String\& | Display name. |
| standard_display_name | const String\& | Standard time name. |
| daylight_display_name | const String\& | Daylight saving time name. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) of adjustment rules. |

### ReturnValue

New time zone.

## See Also

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


| Parameter | Type | Description |
| --- | --- | --- |
| id | const String\& | Time zone identifier. |
| base_utc_offset | TimeSpan | Time interval between the current time zone's standard time and UTC time. |
| display_name | const String\& | Display name. |
| standard_display_name | const String\& | Standard time name. |
| daylight_display_name | const String\& | Daylight saving time name. |
| adjustment_rules | const ArrayPtr\<AdjustmentRulePtr\>\& | [Array](../../array/) of adjustment rules. |
| disable_daylight_saving_time | bool | True to discard any daylight saving time information present in adjustment_rules. |

### ReturnValue

New time zone.

## See Also

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
