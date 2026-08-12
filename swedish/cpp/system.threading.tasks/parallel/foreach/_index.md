---
title: "System::Threading::Tasks::Parallel::ForEach metod"
linktitle: "ForEach"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::Parallel::ForEach metod. Utför en foreach‑operation på ett IEnumerable där iterationer kan köras parallellt i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Utför en foreach-operation på ett IEnumerable där iterationerna kan köras parallellt.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


| Parameter | Beskrivning |
| --- | --- |
| TSource | Typen av data i källan. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | En uppräkningsbar datakälla. |
| body | const Action\<TSource\>\& | Delegaten som anropas en gång per iteration. |

### ReturnValue

En [ParallelLoopResult](../../parallelloopresult/) struktur som innehåller information om vilken del av loopen som slutfördes.
## Anmärkningar



Använder standard‑[ParallelOptions](../../paralleloptions/) med obegränsad parallellism och ingen avbokning.
## Se även

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Utför en foreach-operation på ett IEnumerable där iterationerna kan köras parallellt.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


| Parameter | Beskrivning |
| --- | --- |
| TSource | Typen av data i källan. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | En uppräkningsbar datakälla. |
| parallelOptions | const SharedPtr\<ParallelOptions\>\& | Ett objekt som konfigurerar beteendet för denna operation. |
| body | const Action\<TSource\>\& | Delegaten som anropas en gång per iteration. |

### ReturnValue

En [ParallelLoopResult](../../parallelloopresult/) struktur som innehåller information om vilken del av loopen som slutfördes.
## Anmärkningar



Denna metod partitionerar den uppräkningsbara källan och kör kroppdelegaten på flera trådar samtidigt.
## Se även

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
