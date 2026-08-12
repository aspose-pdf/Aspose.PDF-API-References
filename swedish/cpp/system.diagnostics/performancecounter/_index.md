---
title: "System::Diagnostics::PerformanceCounter-klass"
linktitle: "PerformanceCounter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::PerformanceCounter-klass. Dummy-klass för kod som använder PerformanceCounter och har översatts för att kunna kompileras. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.diagnostics/performancecounter/
---
## PerformanceCounter class


Dummy-klass för kod som använder PerformanceCounter och har översatts för att kunna kompileras. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i pekaren [System::SmartPtr](../../system/smartptr/) och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PerformanceCounter : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() | Stoppar alla prestandaräkningsoperationer. |
| [NextValue](./nextvalue/)() | Hämtar nästa uppmätta värde. |
| [PerformanceCounter](./performancecounter/)() | Skapar prestandaräknare. |
| [PerformanceCounter](./performancecounter/)(const String\&, const String\&) | Skapar prestandaräknare för en specifik kategori. |
| [PerformanceCounter](./performancecounter/)(const String\&, const String\&, const String\&, const String\&) | Skapar prestandaräknare för en specifik kategori och instansnamn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
