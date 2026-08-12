---
title: "System::Diagnostics::Process klass"
linktitle: "Process"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::Process klass. Inkapslar processinformation och manipulation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.diagnostics/process/
---
## Process class


Inkapslar processinformation och manipulation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Process : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_EnableRaisingEvents](./get_enableraisingevents/)() const | Hämtar om händelsen Exited ska utlösas när processen avslutas. |
| [get_ExitCode](./get_exitcode/)() const | Hämtar processens avslutningskod. |
| [get_PrivateMemorySize64](./get_privatememorysize64/)() const | Hämtar processens privata minnesstorlek. |
| [get_ProcessName](./get_processname/)() const | Hämtar processens namn. |
| [get_StandardError](./get_standarderror/)() const | Tillhandahåller läsare för att läsa från processens felutdata. Ej implementerad. |
| [get_StandardOutput](./get_standardoutput/)() const | Tillhandahåller läsare för att läsa från processens standardutdata. Ej implementerad. |
| [get_StartInfo](./get_startinfo/)() const | Hämtar processens startinformation. |
| [get_WorkingSet64](./get_workingset64/)() const | Hämtar processens minnesarbetsuppsättningsstorlek. |
| static [GetCurrentProcess](./getcurrentprocess/)() | Hämtar information om aktuell process. Endast [Windows](../../system.windows/). |
| [GetOutputText](./getoutputtext/)() const | Hämtar processens utdata text. |
| [set_EnableRaisingEvents](./set_enableraisingevents/)(bool) | Ställer in om händelsen Exited ska utlösas när processen avslutas. |
| [Start](./start/)() | Startar process med fördefinierade parametrar. |
| static [Start](./start/)(const String\&, const String\&) | Startar process med angiven sökväg och argument. |
| static [Start](./start/)(const SharedPtr\<ProcessStartInfo\>\&) | Startar process med angiven sökväg och argument. |
| [WaitForExit](./waitforexit/)(int) | Väntar på att processen ska avslutas. Ej implementerat. |
| [WaitForExit](./waitforexit/)() | Väntar på att processen ska avslutas, återvänder inte förrän den är klar. |
| virtual [~Process](./~process/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
