---
title: Aspose::Pdf::Text::OnSegmentChangedEventArgs class
linktitle: OnSegmentChangedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::OnSegmentChangedEventArgs class. Contains additional information about OnSegmentChangedEvent that is delivered to listeners in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.text/onsegmentchangedeventargs/
---
## OnSegmentChangedEventArgs class


Contains additional information about OnSegmentChangedEvent that is delivered to listeners.

```cpp
class OnSegmentChangedEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_InitialSegmentTextLength](./get_initialsegmenttextlength/)() const |  |
| [get_SegmentAfter](./get_segmentafter/)() const |  |
| [get_SegmentChanged](./get_segmentchanged/)() const |  |
| [OnSegmentChangedEventArgs](./onsegmentchangedeventargs/)(System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Segmenting::PhysicalTextSegment\>, System::SharedPtr\<Aspose::Pdf::Engine::CommonData::Text::Segmenting::PhysicalTextSegment\>, int32_t) |  |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
