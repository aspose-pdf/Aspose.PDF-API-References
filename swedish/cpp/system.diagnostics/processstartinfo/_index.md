---
title: "System::Diagnostics::ProcessStartInfo klass"
linktitle: "ProcessStartInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::ProcessStartInfo klass. Beskriver startparametrar för processen. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.diagnostics/processstartinfo/
---
## ProcessStartInfo class


Beskriver startparametrar för processen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ProcessStartInfo : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Arguments](./get_arguments/)() const | Hämtar processargument. |
| [get_CreateNoWindow](./get_createnowindow/)() const | Hämtar NoWindow‑egenskapen. |
| [get_EnvironmentVariables](./get_environmentvariables/)() const | Hämtar processens miljövariabler. |
| [get_FileName](./get_filename/)() const | Hämtar processens filnamn. |
| [get_RedirectStandardError](./get_redirectstandarderror/)() const | Hämtar RedirectStandardError‑egenskapen. |
| [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Hämtar RedirectStandardInput‑egenskapen. |
| [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Hämtar RedirectStandardOutput‑egenskapen. |
| [get_UseShellExecute](./get_useshellexecute/)() const | Hämtar UseShellExecute‑egenskapen. |
| [get_WindowStyle](./get_windowstyle/)() const | Hämtar fönsterstil. |
| [get_WorkingDirectory](./get_workingdirectory/)() const | Hämtar processens arbetskatalog. |
| [ProcessStartInfo](./processstartinfo/)() | Skapar ett tomt startinfo‑objekt. |
| [ProcessStartInfo](./processstartinfo/)(const String\&) | Skapar startinfo‑objekt. |
| [ProcessStartInfo](./processstartinfo/)(const String\&, const String\&) | Skapar startinfo‑objekt. |
| [set_Arguments](./set_arguments/)(const String\&) | Ställer in processargument. |
| [set_CreateNoWindow](./set_createnowindow/)(bool) | Ställer in NoWindow‑egenskapen. |
| [set_FileName](./set_filename/)(const String\&) | Ställer in processens filnamn. |
| [set_RedirectStandardError](./set_redirectstandarderror/)(bool) | Ställer in RedirectStandardError‑egenskapen. |
| [set_RedirectStandardInput](./set_redirectstandardinput/)(bool) | Ställer in RedirectStandardInput‑egenskapen. |
| [set_RedirectStandardOutput](./set_redirectstandardoutput/)(bool) | Ställer in RedirectStandardOutput‑egenskapen. |
| [set_UseShellExecute](./set_useshellexecute/)(bool) | Ställer in UseShellExecute‑egenskapen. |
| [set_WindowStyle](./set_windowstyle/)(ProcessWindowStyle) | Ställer in fönsterstil. |
| [set_WorkingDirectory](./set_workingdirectory/)(const String\&) | Ställer in arbetskatalogen för processen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
