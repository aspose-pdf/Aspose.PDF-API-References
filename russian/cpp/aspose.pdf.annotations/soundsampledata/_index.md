---
title: "Aspose::Pdf::Annotations::SoundSampleData class"
linktitle: "SoundSampleData"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::SoundSampleData class. Представляет дополнительные записи, специфичные для звукового объекта (Section 9.2 PDF1-7) в C++."
type: docs
weight: 10400
url: /ru/cpp/aspose.pdf.annotations/soundsampledata/
---
## SoundSampleData class


Представляет дополнительные записи, специфичные для звукового объекта (Раздел 9.2 PDF1‑7).

```cpp
class SoundSampleData : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BitsPerChannel](./get_bitsperchannel/)() const | Получает количество бит на значение образца для каждого канала. |
| [get_EncodingFormat](./get_encodingformat/)() const | Получает формат кодирования. |
| [get_NumberOfSoundChannels](./get_numberofsoundchannels/)() const | Получает количество звуковых каналов. |
| [get_SamplingRate](./get_samplingrate/)() const | Получает частоту дискретизации. |
| [set_BitsPerChannel](./set_bitsperchannel/)(int32_t) | Устанавливает количество бит на значение образца для каждого канала. |
| [set_EncodingFormat](./set_encodingformat/)(SoundSampleDataEncodingFormat) | Устанавливает формат кодирования. |
| [set_NumberOfSoundChannels](./set_numberofsoundchannels/)(int32_t) | Устанавливает количество звуковых каналов. |
| [set_SamplingRate](./set_samplingrate/)(int64_t) | Устанавливает частоту дискретизации. |
| [SoundSampleData](./soundsampledata/)(int64_t) | Инициализирует новые данные звукового образца. |
| [SoundSampleData](./soundsampledata/)(int64_t, int32_t) | Инициализирует новые данные звукового образца. |
| [SoundSampleData](./soundsampledata/)(int64_t, int32_t, int32_t) | Инициализирует новые данные звукового образца. |
| [SoundSampleData](./soundsampledata/)(int64_t, int32_t, int32_t, SoundSampleDataEncodingFormat) | Инициализирует новые данные звукового образца. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultEncodingFormat](./defaultencodingformat/) | Значение по умолчанию для формата кодирования. |
| static [DefaultOfBitsPerChannel](./defaultofbitsperchannel/) | Значение по умолчанию для параметра BitsPerchannel. |
| static [DefaultOfSoundChannels](./defaultofsoundchannels/) | Значение по умолчанию для параметра Channels. |
| static [DefaultSamplingRate](./defaultsamplingrate/) | Значение по умолчанию для SamplingRate. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
