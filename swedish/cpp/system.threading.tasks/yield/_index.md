---
title: "Metoden System::Threading::Tasks::Yield"
linktitle: "Yield"
second_title: "Aspose.PDF för C++ API-referens"
description: "Metoden System::Threading::Tasks::Yield. Skapar en väntbar uppgift som asynkront återlämnar kontrollen till det aktuella sammanhanget när den väntas i C++."
type: docs
weight: 3200
url: /sv/cpp/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield method


Skapar en väntbar uppgift som asynkront återlämnar kontrollen till det aktuella sammanhanget när den väntas.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### ReturnValue

En YieldAwaitable som kan väntas för att återlämna kontrollen.
## Anmärkningar



Denna metod är användbar för att tvinga en asynkron metod att återlämna kontrollen, så att annat pågående arbete kan bearbetas innan den fortsätter.
## Se även

* Class [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
