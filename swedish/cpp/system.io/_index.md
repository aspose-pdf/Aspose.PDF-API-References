---
title: "System::IO-namespace"
linktitle: "System::IO"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::IO-namespace i C++."
type: docs
weight: 4600
url: /sv/cpp/system.io/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_iostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_istream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_ostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Representerar en buffert som omsluter [System::IO::Stream](./stream/)-liknande strömmar och gör det möjligt att använda dem som en intern buffert för std::iostream-liknande strömmar. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Representerar ett std::iostream-liknande omslag som använder [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Representerar ett std::istream-liknande omslag som använder [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Representerar ett std::ostream-liknande omslag som använder [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BinaryReader](./binaryreader/) | Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BinaryWriter](./binarywriter/) | Representerar en skribent som skriver värden av primitiva typer till en byte-ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BufferedStream](./bufferedstream/) | Lägger till ett buffringslager ovanpå en annan ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Directory](./directory/) | Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [DirectoryInfo](./directoryinfo/) | Representerar en filsökväg, en katalog som refereras av denna sökväg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [File](./file/) | Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [FileInfo](./fileinfo/) | Representerar en sökväg till en fil och en fil som refereras av denna sökväg samt tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [FileStream](./filestream/) | Representerar en filström som stöder synkrona och asynkrona läs- och skrivoperationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [FileSystemInfo](./filesysteminfo/) | Bas-klassen för [FileInfo](./fileinfo/) och [DirectoryInfo](./directoryinfo/). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/) . Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [FileSystemInfoStat](./filesysteminfostat/) | Representerar information om en fil eller katalog. |
| [MemoryStream](./memorystream/) | Representerar en ström som läser från och skriver till minnet. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Path](./path/) | Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Representerar en basklass för omslag liknande [System.IO.Stream](./stream/). Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Stream](./stream/) | En basklass för en mängd olika strömmimplementeringar. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan orsaka körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StreamReader](./streamreader/) | Representerar en läsare som läser tecken från en byte‑ström. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StreamWriter](./streamwriter/) | Representerar en skribent som skriver tecken till en byte‑ström. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan orsaka körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StringReader](./stringreader/) | Representerar en läsare som läser tecken från en sträng. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StringWriter](./stringwriter/) | Implementerar en [TextWriter](./textwriter/) som skriver information till en sträng. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [TextReader](./textreader/) | En basklass för klasser som representerar läsare som läser sekvenser av tecken från olika källor. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [TextWriter](./textwriter/) | En basklass för klasser som representerar skribenter som skriver sekvenser av tecken till olika destinationer. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan orsaka körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Tillhandahåller åtkomst till ohanterat minne. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [FileAccess](./fileaccess/) | Anger åtkomsttypen när filen öppnas. |
| [FileAttributes](./fileattributes/) | Representerar attribut för en katalog eller en fil. |
| [FileMode](./filemode/) | Anger hur en fil ska öppnas. |
| [FileOptions](./fileoptions/) | Representerar avancerade alternativ för att skapa ett [FileStream](./filestream/)‑objekt. |
| [FileShare](./fileshare/) | Anger vilken typ av åtkomst andra [FileStream](./filestream/)‑objekt kan ha till en fil som öppnas. |
| [SearchOption](./searchoption/) | Anger att en sökning ska utföras endast i den aktuella katalogen, eller i den aktuella katalogen och alla dess underkataloger. |
| [SeekOrigin](./seekorigin/) | Anger referenspositionen i strömmen relativt vilken den position som ska sökas till anges. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Bestämmer vilken position i strömmen som är föredragen som gemensam läs‑ och skrivposition när std::basic_iostream och dess avledda klasser har olika läs‑ och skrivpositioner vid omslagsskapandet. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Anger läget för I/O‑operationer som omslag kommer att utföra på strömmar liknande std::iostreams. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Anger läget för I/O‑operationer som omslag kommer att utföra på strömmar liknande [System::IO::Stream](./stream/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BinaryWriterPtr](./binarywriterptr/) | Ett alias för en delad pekare till denna klass. |
| [FileNotFoundException](./filenotfoundexception/) | Undantaget som kastas när ett försök att komma åt en fil som inte finns på disken misslyckas. Omslut aldrig instanser av klassen [FileNotFoundException](./filenotfoundexception/) i en [System::SmartPtr](../system/smartptr/). |
| [IsTemplateBaseOf](./istemplatebaseof/) | Representerar motsvarigheten till std::is_base_of<Base, Derived> som bestämmer arv från en icke‑instanserad Base‑mallklass till en instanserad Derived‑mallklass. Kommer att misslyckas vid multipelt arv eller icke‑publikt arv från Base. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specialiseringar av [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) för teckentypen char. |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specialiseringar av [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) för char-teckentyper. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specialiseringar av [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) för char-teckentyper. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specialiseringar av [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) för wchar_t-teckentyper. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specialiseringar av [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) för wchar_t-teckentyper. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specialiseringar av [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) för wchar_t-teckentyper. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specialiseringar av [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) för char-teckentyper. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specialiseringar av [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) för char-teckentyper. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specialiseringar av [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) för char-teckentyper. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specialiseringar av [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) för wchar_t-teckentyper. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specialiseringar av [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) för wchar_t-teckentyper. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specialiseringar av [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) för wchar_t-teckentyper. |
## Functions

| Funktion | Beskrivning |
| --- | --- |
| WrapSTDIOStream | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| WrapSTDIOStream | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| WrapSTDIOStream | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
