---
title: "System::With metod"
linktitle: "With"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::With metod. Klonar referenspost och tillämpar initieringsfunktor på den i C++."
type: docs
weight: 44900
url: /sv/cpp/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) method


Klonar referenspost och tillämpar initieringsfunktor på den.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Posttyp att klona. |
| A | Initieringsfunktor-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | const SharedPtr\<T\>\& | Delad pekare till objektet som ska klonas och initieras. |
| initialiserare | const A\& | Initieringsfunktor som tillämpas på postklon. |

### ReturnValue

Delad pekare till klonad post.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::With(const T\&, const A\&) method


Kopierar struct record och tillämpar initialiseringsfunktor på den.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Posttyp att kopiera. |
| A | Initieringsfunktor-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | const T\& | Post att kopiera och initiera. |
| initialiserare | const A\& | Initieringsfunktor som tillämpas på postkopian. |

### ReturnValue

Kopierad post.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
