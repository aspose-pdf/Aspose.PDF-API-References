---
title: System namespace
linktitle: System
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System namespace in C++.'
type: docs
weight: 2700
url: /cpp/system/
---



## Classes

| Class | Description |
| --- | --- |
| [Activator](./activator/) | Contains methods to create types of objects. |
| [Array](./array/) | Class that represents an array data structure. Objects of this class should only be allocated using [System::MakeArray()](./makearray/) and [System::MakeObject()](./makeobject/) functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ArraySegment](./arraysegment/) | Represents a segment of the one-dimensional array. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Attribute](./attribute/) | A base class for custom attributes. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BitConverter](./bitconverter/) | Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means. |
| [Boolean](./boolean/) | Class that keeps static members of [System.Boolean](./boolean/) .[Net](../system.net/) type. |
| [BoxedEnum](./boxedenum/) | Represents boxed enumeration value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BoxedValue](./boxedvalue/) | Represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BoxedValueBase](./boxedvaluebase/) | A base class that defines an interface and implements some fundamental methods of a descendant class that represents a boxed value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Buffer](./buffer/) | Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means. |
| [Byte](./byte/) | Contains methods to work with the unsigned 8-bit integer. |
| [Char](./char/) | Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means. |
| [Comparison](./comparison/) | Represents a pointer to the method that compares two objects of the same type. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Console](./console/) | Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means. |
| [ConsoleOutput](./consoleoutput/) | Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [DateTime](./datetime/) | Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [DateTimeOffset](./datetimeoffset/) | Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [DBNull](./dbnull/) | Represents a non-existing value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Decimal](./decimal/) | Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Represents a pointer to a function, method or a function object. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [DynamicWeakPtr](./dynamicweakptr/) | Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [EnumValues](./enumvalues/) | Provides meta information about enumeration constants of enum type **E**. |
| [EnumValuesBase](./enumvaluesbase/) | A base class for a class that represents meta information of enumeration type. |
| [EventArgs](./eventargs/) | The base class for classes that represent a context that is passed to the event subscribers when an event is triggered. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ExceptionWrapper](./exceptionwrapper/) | Template that represents wrapper of exceptions that are derived from [Exception](./exception/) class. |
| [FlagsAttribute](./flagsattribute/) | Indicates that an enumeration can be treated as a bit field; that is, a set of. |
| [Func](./func/) | Function delegate. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [GC](./gc/) | Represents an emulated Garbage Collection which acts more like a stub which effectively does nothing. This is a static type with no instance services. You should never create instances of it by any means. |
| [Guid](./guid/) | Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [IAsyncResult](./iasyncresult/) | Represents the status of asynchronous operation. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ICloneable](./icloneable/) | Defies a method that enables object cloning - creating a copy of an object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IComparable](./icomparable/) | Defines a method that compares two objects. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IConvertible](./iconvertible/) | Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ICustomFormatter](./icustomformatter/) | Defines a method that performs custom formatting of a string representation of a value represented by the specified object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IDisposable](./idisposable/) | Defines method that releases resources owned by the current object. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IEquatable](./iequatable/) | Defines a method that determines the equality of two objects. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IFormatProvider](./iformatprovider/) | Defines a method that provides formatting information. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IFormattable](./iformattable/) | Defines a method that formats the value of the current object using the specified format string and format provider. |
| [Int16](./int16/) | Contains methods to work with the 16-bit integer. |
| [Int32](./int32/) | Contains methods to work with the 32-bit integer. |
| [Int64](./int64/) | Contains methods to work with the 64-bit integer. |
| [LockContext](./lockcontext/) | Guard object implementing C# lock() statement. |
| [MarshalByRefObject](./marshalbyrefobject/) | Provides access to objects across application domain boundaries in remoting-enabled applications. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Nullable](./nullable/) | Forward declaration. |
| [NullableUtils](./nullableutils/) | Represents C# [System.Nullable](./nullable/) (with no type arguments) static class. Unable to use original name due inability to overload class templates in C++. Supports a value type that can be assigned null. This class cannot be inherited. |
| [Object](./object/) | Base class that enables using methods available for [System.Object](./object/) class in C#. All non-trivial classes used with translated environment should inherit it. |
| [ObjectExt](./objectext/) | Provides static methods that emulate C# [Object](./object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means. |
| [ObjectType](./objecttype/) | Provides static methods that implement object type getters. This is a static type with no instance services. You should never create instances of it by any means. |
| [OperatingSystem](./operatingsystem/) | Represents a particular operating system and provides information about it. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Random](./random/) | Represents a pseudo-random number generator. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ReadOnlySpan](./readonlyspan/) | Forward to use within [Span](./span/) class. |
| [ScopedCulture](./scopedculture/) | Represents a culture used within the scope. |
| [SmartPtr](./smartptr/) | Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](./object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](./object/) itself or in counter structure which is tied to [Object](./object/) instance tightly. In any case, all [SmartPtr](./smartptr/) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./smartptr/) is safe given there are other [SmartPtr](./smartptr/) instances holding shared references to the same object. [SmartPtr](./smartptr/) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](./object/) is being deleted when the last 'shared' [SmartPtr](./smartptr/) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./smartptr/) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](./weakptr/) pointer class or [System::SmartPtrMode::Weak](./smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) method or [System::DynamicWeakPtr](./dynamicweakptr/) class. [SmartPtr](./smartptr/) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [SmartPtrInfo](./smartptrinfo/) | Service class to test and alter [SmartPtr](./smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](./smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class. |
| [Span](./span/) | Represents a contiguous region of arbitrary memory similar to C++20's std::span. |
| [String](./string/) | [String](./string/) class used across the library. Is a substitute for C# [System.String](./string/) when translating code. For optimization reasons, isn't considered an [Object](./object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [StringComparer](./stringcomparer/) | Compares strings using different comparison modes. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [StringHashCompiletime](./stringhashcompiletime/) | A helper class that generates a hash value from a c-string. |
| [TimeSpan](./timespan/) | Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [TimeZone](./timezone/) | Represents a time zone. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [TimeZoneInfo](./timezoneinfo/) | Represents an information destribing a particular time zone. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Tuple](./tuple/) | Class that represents a tuple data structure. Maximum number of items is 8. |
| [TupleFactory](./tuplefactory/) | Provides static methods for creating tuple objects. |
| [TypeInfo](./typeinfo/) | Represents a particular type and provides information about it. |
| [Uri](./uri/) | Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriBuilder](./uribuilder/) | Provides methods to construct and modify universial resource identifiers (URIs). Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriParser](./uriparser/) | Used to parse a new URI scheme. Objects of this class should only be allocated using [System::MakeObject()](./makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](./smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UriShim](./urishim/) | Service class. |
| [ValueTuple](./valuetuple/) | Class that represents a [ValueTuple](./valuetuple/) data structure. |
| [ValueType](./valuetype/) | Baseclass for value types with [Object](./object/) inheritance being truncated for performance reasons. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Version](./version/) | Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Subclass of [System::SmartPtr](./smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](./smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [WeakReference](./weakreference/) | Represents a weak reference, which references an object while still allowing that object to be deleted. |
| [WeakReference< T >](./weakreference_t_/) | Represents a weak reference, which references an object while still allowing that object to be deleted. |
| [WeakReference<>](./weakreference__/) | Represents a weak reference, which references an object while still allowing that object to be deleted. |
## Enums

| Enum | Description |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Enumeration containing values that represent different formats of base-64 encoded data. |
| [DateTimeKind](./datetimekind/) | Enumeration values of which represent the kinds of date and time. |
| [DayOfWeek](./dayofweek/) | Enumeration that represents a day of week. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Specifies the environment variable location. |
| [MidpointRounding](./midpointrounding/) | Specifies the behavior of rounding functions. |
| [PlatformID](./platformid/) | Represents an operating system platform. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) pointer type: weak or shared. Defines whether pointer is being counted when it is being decided whether to delete object or not. |
| [StringComparison](./stringcomparison/) | Defines string comparison style. |
| [StringSplitOptions](./stringsplitoptions/) | Determines string splitting behavior. |
| [TypeCode](./typecode/) | Represents the type of an object. |
| [UriComponents](./uricomponents/) | Represents URI components. |
| [UriFormat](./uriformat/) | Specifies how the URI is escaped. |
| [UriHostNameType](./urihostnametype/) | Represents the type of host name. |
| [UriKind](./urikind/) | Represents the kinds of URIs. |
| [UriPartial](./uripartial/) | Represents the parts of a URI for the [Uri.GetLeftPart](./uri/getleftpart/) method. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Action](./action/) | Delegate type that references methods that have no return value. |
| [ArrayPtr](./arrayptr/) | Alias for 'pointer to array' type. |
| [AsyncCallback](./asynccallback/) | A delegate type that represents a method to be called when asynchronous operation completes. |
| [BadImageFormatException](./badimageformatexception/) | The exception that is thrown when the file image of a dynamic link library (DLL) or an executable program is invalid. Never wrap the [BadImageFormatException](./badimageformatexception/) class instances into [System::SmartPtr](./smartptr/). |
| [ByteArrayPtr](./bytearrayptr/) | An alias for a smart pointer object that points to an array of unsigned 8-bit integers. |
| [Converter](./converter/) | Represents a pointer to the invokable entity that accepts a single argument of the **TInput** type and returns a value of the **TOutput** type. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) class. |
| [DecoderFallbackPtr](./decoderfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderFallback](../system.text/decoderfallback/) class. |
| [DecoderPtr](./decoderptr/) | An alias for a smart pointer that points to an instance of [System::Text::Decoder](../system.text/decoder/) class. |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) class. |
| [DirectoryInfoPtr](./directoryinfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::DirectoryInfo](../system.io/directoryinfo/) class. |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) class. |
| [EncoderFallbackPtr](./encoderfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderFallback](../system.text/encoderfallback/) class. |
| [EncoderPtr](./encoderptr/) | An alias for a smart pointer that points to an instance of [System::Text::Encoder](../system.text/encoder/) class. |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) class. |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) class. |
| [EncodingInfoPtr](./encodinginfoptr/) | An alias for a smart pointer that points to an instance of [System::Text::EncodingInfo](../system.text/encodinginfo/) class. |
| [EncodingPtr](./encodingptr/) | An alias for a smart pointer that points to an instance of [System::Text::Encoding](../system.text/encoding/) class. |
| [Event](./event/) | Represents an event - a mechanism through which subscribers are notified about an occurence of interest by means of a delegate invocation. |
| [EventArgsPtr](./eventargsptr/) | Shared pointer to an instance of [EventArgs](./eventargs/) class. |
| [EventHandler](./eventhandler/) | Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](./smartptr/) class to manage objects of this type. |
| [Exception](./exception/) | Alias to be used instead of Details::Exception. |
| [ExceptionPtr](./exceptionptr/) | Type alias used by exception wrappers. |
| [FileInfoPtr](./fileinfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileInfo](../system.io/fileinfo/) class. |
| [FileStreamPtr](./filestreamptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileStream](../system.io/filestream/) class. |
| [FileSystemInfoPtr](./filesysteminfoptr/) | An alias for a smart pointer that points to an instance of [System::IO::FileSystemInfo](../system.io/filesysteminfo/) class. |
| [FunctionPtr](./functionptr/) | An alias for function type with default calling convention. |
| [IAsyncResultPtr](./iasyncresultptr/) | Shared pointer to [IAsyncResult](./iasyncresult/). |
| [IFormatProviderPtr](./iformatproviderptr/) | An alias for a smart pointer that points to an instance of [System::IFormatProvider](./iformatprovider/) class. |
| [MakeConstRef_t](./makeconstref_t/) | Helper type for [MakeConstRef](./makeconstref/) modifier. |
| [MemoryStreamPtr](./memorystreamptr/) | An alias for a smart pointer that points to an instance of [System::IO::MemoryStream](../system.io/memorystream/) class. |
| [Predicate](./predicate/) | Represents a pointer to a predicate - an invokable entity that accepts a single argument and returns a bool value. |
| [RTaskPtr](./rtaskptr/) | An alias for a smart pointer that points to an instance of [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) class. |
| [SharedPtr](./sharedptr/) | Alias for smart pointer widely used in the library. |
| [StreamPtr](./streamptr/) | An alias for a smart pointer that points to an instance of [System::IO::Stream](../system.io/stream/) class. |
| [StreamReaderPtr](./streamreaderptr/) | An alias for a smart pointer that points to an instance of [System::IO::StreamReader](../system.io/streamreader/) class. |
| [StreamWriterPtr](./streamwriterptr/) | An alias for a smart pointer that points to an instance of [System::IO::StreamWriter](../system.io/streamwriter/) class. |
| [StringComparerPtr](./stringcomparerptr/) | An alias for a shared pointer to an instance of [StringComparer](./stringcomparer/) class. |
| [TaskPtr](./taskptr/) | An alias for a smart pointer that points to an instance of [System::Threading::Tasks::Task](../system.threading.tasks/task/) class. |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias for shared pointer to an instance of [TimeZoneInfo](./timezoneinfo/) class. |
| [TimeZonePtr](./timezoneptr/) | Shared pointer to an instance of [TimeZone](./timezone/) class. |
## Functions

| Function | Description |
| --- | --- |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Build | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| BuildObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CheckedCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| const_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConstCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Discard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| dynamic_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForceStaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForEachMemberGVName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| get_pointer | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_parametrized_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_vp_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsConstant | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsDeclaration | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNegativeInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPositiveInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeScopeGuard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerable | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerator | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MemberwiseClone | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| SafeInvoke | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| static_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| TieTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
