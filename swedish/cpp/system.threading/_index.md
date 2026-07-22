---
title: "System::Threading-namespace"
linktitle: "System::Threading"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Threading-namespace i C++."
type: docs
weight: 7200
url: /sv/cpp/system.threading/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | [Event](../system/event/) för att meddela väntande tråd som återställs automatiskt. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [CancellationToken](./cancellationtoken/) | Sprider en notifikation om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för samarbetsbaserad avbrytning mellan trådar, vilket gör att en tråd kan meddela andra att en operation bör avbrytas. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Representerar en registrering för en avbokningstoken-återuppringning. |
| [CancellationTokenSource](./cancellationtokensource/) | En avbokningstokenkälla som kan användas för att utlösa avbokningsnotifikationer. |
| [EventWaitHandle](./eventwaithandle/) | [Event](../system/event/) som kan skickas till en väntande tråd. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Interlocked](./interlocked/) | Tillhandahåller API för trådsäkra operationer. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt. |
| [ManualResetEvent](./manualresetevent/) | [Event](../system/event/) för att meddela en väntande tråd som inte återställs automatiskt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Monitor](./monitor/) | Klassen [Monitor](./monitor/) tillhandahåller en mekanism som synkroniserar åtkomst till objekt. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [SynchronizationContext](./synchronizationcontext/) | Tillhandahåller grundläggande funktionalitet för att sprida ett synkroniseringssammanhang över olika synkroniseringsoperationer. |
| [Thread](./thread/) | [Thread](./thread/) implementation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool-API som tillåter att den skjuter jobb i en kö som läses av en pool av arbetstrådar. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) pool intern data. Detta är en singleton-typ med minneshantering som sköts av åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt. |
| [Timer](./timer/) | [Timer](./timer/) klass som kör ett jobb i en separat tråd efter en fördröjning. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [TimerQueue](./timerqueue/) | Kö som hanterar [Timer](./timer/) objekt. Detta är bara en implementation. [Timer](./timer/) objekt registrerar sig själva där, du behöver inte göra det för att använda dem – använd [Timer](./timer/) klass-API istället. Detta är en singleton-typ med minneshantering som sköts av åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt. |
| [WaitHandle](./waithandle/) | Väntande primitiv basklass. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Ställer in apartment-tillståndet för tråden. |
| [EventResetMode](./eventresetmode/) | Indikerar hur händelsetillståndet återställs. |
| [ThreadState](./threadstate/) | Tillstånd för tråden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) funktion med en parameter. |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ThreadStart](./threadstart/) | [Thread](./thread/) funktion utan parametrar. |
| [TimerCallback](./timercallback/) | Återuppringningsfunktion som ska anropas av timer. |
| [wait_handle_t](./wait_handle_t/) | Handtagstyp. |
| [WaitCallback](./waitcallback/) | Återuppringningsobjekt som ska köras när det finns en plats. |
