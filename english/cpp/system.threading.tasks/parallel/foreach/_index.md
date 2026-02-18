---
title: System::Threading::Tasks::Parallel::ForEach method
linktitle: ForEach
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Parallel::ForEach method. Executes a foreach operation on an IEnumerable in which iterations may run in parallel in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Executes a foreach operation on an IEnumerable in which iterations may run in parallel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

| Parameter | Type | Description |
| --- | --- | --- |
| source | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | An enumerable data source. |
| body | const Action\<TSource\>\& | The delegate that is invoked once per iteration. |

### ReturnValue

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Remarks



Uses default [ParallelOptions](../../paralleloptions/) with unlimited parallelism and no cancellation. 
## See Also

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Executes a foreach operation on an IEnumerable in which iterations may run in parallel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

| Parameter | Type | Description |
| --- | --- | --- |
| source | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const SharedPtr\<ParallelOptions\>\& | An object that configures the behavior of this operation. |
| body | const Action\<TSource\>\& | The delegate that is invoked once per iteration. |

### ReturnValue

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Remarks



This method partitions the source enumerable and executes the body delegate on multiple threads concurrently. 
## See Also

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
