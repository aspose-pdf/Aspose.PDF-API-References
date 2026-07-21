---
title: "System::Threading::Tasks::Parallel::ForEach método"
linktitle: "ForEach"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::Parallel::ForEach método. Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo en C++."
type: docs
weight: 100
url: /es/cpp/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


| Parámetro | Descripción |
| --- | --- |
| TSource | El tipo de los datos en la fuente. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | Una fuente de datos enumerable. |
| body | const Action\<TSource\>\& | El delegado que se invoca una vez por iteración. |

### ReturnValue

Una estructura [ParallelLoopResult](../../parallelloopresult/) que contiene información sobre qué parte del bucle se completó.
## Observaciones



Utiliza [ParallelOptions](../../paralleloptions/) predeterminadas con paralelismo ilimitado y sin cancelación.
## Ver también

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


| Parámetro | Descripción |
| --- | --- |
| TSource | El tipo de los datos en la fuente. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\& | Una fuente de datos enumerable. |
| parallelOptions | const SharedPtr\<ParallelOptions\>\& | Un objeto que configura el comportamiento de esta operación. |
| body | const Action\<TSource\>\& | El delegado que se invoca una vez por iteración. |

### ReturnValue

Una estructura [ParallelLoopResult](../../parallelloopresult/) que contiene información sobre qué parte del bucle se completó.
## Observaciones



Este método divide la fuente enumerable y ejecuta el delegado body en múltiples hilos concurrentemente.
## Ver también

* Class [ParallelLoopResult](../../parallelloopresult/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Typedef [Action](../../../system/action/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
