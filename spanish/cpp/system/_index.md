---
title: "Espacio de nombres System"
linktitle: "System"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el espacio de nombres System en C++."
type: docs
weight: 2800
url: /es/cpp/system/
---



## Clases

| Clase | Descripción |
| --- | --- |
| [Activator](./activator/) | Contiene métodos para crear tipos de objetos. |
| [Array](./array/) | Clase que representa una estructura de datos de arreglo. Los objetos de esta clase solo deben asignarse usando las funciones [System::MakeArray()](./makearray/) y [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [ArrayBase](./arraybase/) | El simulacro para la clase [System.Array](./array/) (clase base abstracta para todos los arreglos) puede llenarse con funcionalidad bajo solicitud. |
| [ArraySegment](./arraysegment/) | Representa un segmento del arreglo unidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Attribute](./attribute/) | Clase base para atributos personalizados. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [BitConverter](./bitconverter/) | Contiene métodos que realizan conversiones de secuencias de bytes a un tipo de valor y viceversa. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Boolean](./boolean/) | Clase que mantiene miembros estáticos del tipo [System.Boolean](./boolean/) .[Net](../system.net/). |
| [BoxedEnum](./boxedenum/) | Representa un valor de enumeración empaquetado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [BoxedValue](./boxedvalue/) | Representa un valor empaquetado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [BoxedValueBase](./boxedvaluebase/) | Clase base que define una interfaz e implementa algunos métodos fundamentales de una clase descendiente que representa un valor empaquetado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [Buffer](./buffer/) | Contiene métodos que manipulan arreglos de bytes sin procesar. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Byte](./byte/) | Contiene métodos para trabajar con el entero sin signo de 8 bits. |
| [Char](./char/) | Proporciona métodos para la manipulación de caracteres representados como unidades de código UTF-16. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Comparison](./comparison/) | Representa un puntero al método que compara dos objetos del mismo tipo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Console](./console/) | Proporciona métodos para enviar datos al flujo de salida estándar. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [ConsoleOutput](./consoleoutput/) | Representa el flujo de salida estándar. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [DateTime](./datetime/) | Representa un valor específico de fecha y hora en el continuo temporal. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [DateTimeOffset](./datetimeoffset/) | Contiene la fecha y hora del día relativa al Tiempo Universal Coordinado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [DBNull](./dbnull/) | Representa un valor inexistente. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [Decimal](./decimal/) | Representa un número decimal. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) implementación de clase. Permite que las especializaciones de BoxingValue se declaren sin duplicar código común. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Representa un puntero a una función, método o un objeto función. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [DynamicWeakPtr](./dynamicweakptr/) | Clase de puntero inteligente que rastrea los modos de puntero de los argumentos de plantilla del objeto almacenado y los actualiza después de cada asignación. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante. |
| [EnumValues](./enumvalues/) | Proporciona información meta sobre las constantes de enumeración del tipo enum **E**. |
| [EnumValuesBase](./enumvaluesbase/) | Una clase base para una clase que representa información meta de un tipo de enumeración. |
| [EventArgs](./eventargs/) | La clase base para clases que representan un contexto que se pasa a los suscriptores de eventos cuando se dispara un evento. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [ExceptionWrapper](./exceptionwrapper/) | Plantilla que representa un contenedor de excepciones que derivan de la clase [Exception](./exception/). |
| [FlagsAttribute](./flagsattribute/) | Indica que una enumeración puede tratarse como un campo de bits; es decir, un conjunto de. |
| [Func](./func/) | Delegado de función. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [GC](./gc/) | Representa una recolección de basura emulada que actúa más como un stub que efectivamente no hace nada. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Guid](./guid/) | Representa un Identificador Globalmente Único. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [IAsyncResult](./iasyncresult/) | Representa el estado de una operación asíncrona. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [ICloneable](./icloneable/) | Define un método que permite clonar objetos - crear una copia de un objeto. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IComparable](./icomparable/) | Define un método que compara dos objetos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IConvertible](./iconvertible/) | Define métodos que convierten el valor del tipo de referencia o valor que implementa a un tipo del Common Language Runtime que tiene un valor equivalente. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [ICustomFormatter](./icustomformatter/) | Define un método que realiza un formato personalizado de la representación en cadena de un valor representado por el objeto especificado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IDisposable](./idisposable/) | Define un método que libera los recursos poseídos por el objeto actual. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IEquatable](./iequatable/) | Define un método que determina la igualdad de dos objetos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IFormatProvider](./iformatprovider/) | Define un método que proporciona información de formato. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IFormattable](./iformattable/) | Define un método que formatea el valor del objeto actual usando la cadena de formato y el proveedor de formato especificados. |
| [Index](./index/) | Representa un índice en una colección. El índice puede ser desde el inicio o desde el final. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Int16](./int16/) | Contiene métodos para trabajar con el entero de 16 bits. |
| [Int32](./int32/) | Contiene métodos para trabajar con el entero de 32 bits. |
| [Int64](./int64/) | Contiene métodos para trabajar con el entero de 64 bits. |
| [LockContext](./lockcontext/) | Objeto de guardia que implementa la sentencia lock() de C#. |
| [MarshalByRefObject](./marshalbyrefobject/) | Proporciona acceso a objetos a través de los límites del dominio de la aplicación en aplicaciones habilitadas para remoting. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Representa una colección de delegados. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Nullable](./nullable/) | Declaración adelantada. |
| [NullableUtils](./nullableutils/) | Representa la clase estática C# [System.Nullable](./nullable/) (sin argumentos de tipo). No es posible usar el nombre original debido a la imposibilidad de sobrecargar plantillas de clase en C++. Soporta un tipo de valor que puede asignarse a null. Esta clase no puede heredarse. |
| [Object](./object/) | Clase base que permite usar los métodos disponibles para la clase [System.Object](./object/) en C#. Todas las clases no triviales utilizadas con el entorno traducido deben heredarla. |
| [ObjectExt](./objectext/) | Proporciona métodos estáticos que emulan los métodos de C# [Object](./object/) llamados para tipos C++ que no son Object (cadenas, números, etc.). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [ObjectType](./objecttype/) | Proporciona métodos estáticos que implementan getters de tipo de objeto. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [OperatingSystem](./operatingsystem/) | Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Random](./random/) | Representa un generador de números pseudoaleatorios. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Range](./range/) | Representa un rango con un índice de inicio y fin. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [ReadOnlySpan](./readonlyspan/) | Adelanto para usar dentro de la clase [Span](./span/). |
| [ScopedCulture](./scopedculture/) | Representa una cultura utilizada dentro del ámbito. |
| [SmartPtr](./smartptr/) | Clase de puntero para envolver tipos que se asignan en el montón. Úsela para gestionar la memoria de clases que heredan de [Object](./object/). Este tipo de puntero sigue la semántica de punteros intrusivos. El contador de referencias se almacena ya sea en el propio [Object](./object/) o en una estructura de contador que está estrechamente vinculada a la instancia de [Object](./object/). En cualquier caso, todas las instancias de [SmartPtr](./smartptr/) forman un único grupo de propiedad sin importar cómo fueron creadas, lo que difiere del comportamiento de la clase std::shared_ptr. Convertir un puntero crudo a [SmartPtr](./smartptr/) es seguro siempre que existan otras instancias de [SmartPtr](./smartptr/) que mantengan referencias compartidas al mismo objeto. Una instancia de la clase [SmartPtr](./smartptr/) puede estar en uno de dos estados: puntero compartido y puntero débil. Para mantener vivo el objeto, debe haber un recuento positivo de referencias compartidas a él. Tanto los punteros débiles como los compartidos pueden usarse para acceder al objeto apuntado (llamar a métodos, leer o escribir campos, etc.), pero los punteros débiles no participan en el recuento de referencias del puntero compartido. El [Object](./object/) se elimina cuando se destruye el último puntero 'shared' [SmartPtr](./smartptr/) que lo apunta. Por lo tanto, asegúrese de que esto no ocurra cuando no existan otros punteros [SmartPtr](./smartptr/) compartidos al objeto, por ejemplo durante la construcción o destrucción del objeto. Use los objetos centinela System::Object::ThisProtector (en código C++) o los atributos CppCTORSelfReference o CppSelfReference (en código C# traducido) para corregir este problema. De manera similar, asegúrese de romper referencias cíclicas usando la clase de puntero [System::WeakPtr](./weakptr/) o el modo de puntero [System::SmartPtrMode::Weak](./smartptrmode/) (en código C++) o el atributo CppWeakPtr (en código C# traducido). Si dos o más objetos se referencian mutuamente usando punteros 'shared', nunca se eliminarán. Si el tipo de puntero (débil o compartido) debe cambiarse en tiempo de ejecución, use el método [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) o la clase [System::DynamicWeakPtr](./dynamicweakptr/). La clase [SmartPtr](./smartptr/) no contiene métodos virtuales. Solo debe heredarse si está creando su propia estrategia de gestión de memoria. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante. |
| [SmartPtrInfo](./smartptrinfo/) | Clase de servicio para probar y modificar el contenido de [SmartPtr](./smartptr/) sin conocer el tipo final. Se utiliza para la recolección de basura y la detección de referencias cíclicas, etc. Piénsela como un 'puntero a puntero'. No podemos usar el tipo base de [SmartPtr](./smartptr/) ya que no tiene ninguno; en su lugar, usamos esta clase 'info'. |
| [Span](./span/) | Representa una región contigua de memoria arbitraria similar a std::span de C++20. |
| [String](./string/) | Clase [String](./string/) utilizada en toda la biblioteca. Es un sustituto de [System.String](./string/) de C# al traducir código. Por razones de optimización, no se considera una subclase de [Object](./object/). Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [StringComparer](./stringcomparer/) | Compara cadenas usando diferentes modos de comparación. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [StringHashCompiletime](./stringhashcompiletime/) | Clase auxiliar que genera un valor hash a partir de una cadena C. |
| [TimeSpan](./timespan/) | Representa un intervalo de tiempo. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [TimeZone](./timezone/) | Representa una zona horaria. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [TimeZoneInfo](./timezoneinfo/) | Representa información que describe una zona horaria particular. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Tuple](./tuple/) | Clase que representa una estructura de datos de tupla. El número máximo de elementos es 8. |
| [TupleFactory](./tuplefactory/) | Proporciona métodos estáticos para crear objetos de tupla. |
| [TypeInfo](./typeinfo/) | Representa un tipo particular y proporciona información sobre él. |
| [Uri](./uri/) | Identificador de recurso unificado. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [UriBuilder](./uribuilder/) | Proporciona métodos para construir y modificar identificadores universales de recursos (URIs). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [UriParser](./uriparser/) | Se usa para analizar un nuevo esquema URI. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](./makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](./smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [UriShim](./urishim/) | Clase de servicio. |
| [ValueTuple](./valuetuple/) | Clase que representa una estructura de datos [ValueTuple](./valuetuple/). |
| [ValueType](./valuetype/) | Clase base para tipos de valor con herencia de [Object](./object/) truncada por razones de rendimiento. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Version](./version/) | Representa un número de versión. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Subclase de [System::SmartPtr](./smartptr/) que se establece en modo débil en la construcción. Tenga en cuenta que esta clase no garantiza que su instancia permanezca siempre en modo débil, ya que [set_Mode()](./smartptr/set_mode/) sigue siendo accesible. Este tipo es un puntero para gestionar la eliminación de otros objetos. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante. |
| [WeakReference](./weakreference/) | Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado. |
| [WeakReference< T >](./weakreference_t_/) | Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado. |
| [WeakReference<>](./weakreference__/) | Representa una referencia débil, que referencia a un objeto mientras aún permite que ese objeto sea eliminado. |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Enumeración que contiene valores que representan diferentes formatos de datos codificados en base-64. |
| [DateTimeKind](./datetimekind/) | Valores de enumeración que representan los tipos de fecha y hora. |
| [DayOfWeek](./dayofweek/) | Enumeración que representa un día de la semana. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Especifica la ubicación de la variable de entorno. |
| [MidpointRounding](./midpointrounding/) | Especifica el comportamiento de las funciones de redondeo. |
| [PlatformID](./platformid/) | Representa una plataforma del sistema operativo. |
| [SmartPtrMode](./smartptrmode/) | Tipo de puntero [SmartPtr](./smartptr/): débil o compartido. Define si el puntero se cuenta al decidir si eliminar el objeto o no. |
| [StringComparison](./stringcomparison/) | Define el estilo de comparación de cadenas. |
| [StringSplitOptions](./stringsplitoptions/) | Determina el comportamiento de división de cadenas. |
| [TypeCode](./typecode/) | Representa el tipo de un objeto. |
| [UriComponents](./uricomponents/) | Representa los componentes de una URI. |
| [UriFormat](./uriformat/) | Especifica cómo se escapa la URI. |
| [UriHostNameType](./urihostnametype/) | Representa el tipo de nombre de host. |
| [UriKind](./urikind/) | Representa los tipos de URIs. |
| [UriPartial](./uripartial/) | Representa las partes de una URI para el método [Uri.GetLeftPart](./uri/getleftpart/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Action](./action/) | Tipo de delegado que referencia métodos que no devuelven valor. |
| [AggregateException](./aggregateexception/) |  |
| [ArrayPtr](./arrayptr/) | Alias para el tipo 'puntero a matriz'. |
| [AsyncCallback](./asynccallback/) | Un tipo de delegado que representa un método que se llamará cuando la operación asíncrona finalice. |
| [BadImageFormatException](./badimageformatexception/) | La excepción que se lanza cuando la imagen de archivo de una biblioteca de enlace dinámico (DLL) o de un programa ejecutable es inválida. Nunca envuelva las instancias de la clase [BadImageFormatException](./badimageformatexception/) en [System::SmartPtr](./smartptr/). |
| [ByteArrayPtr](./bytearrayptr/) | Un alias para un objeto smart pointer que apunta a una matriz de enteros sin signo de 8 bits. |
| [Converter](./converter/) | Representa un puntero a la entidad invocable que acepta un único argumento del tipo **TInput** y devuelve un valor del tipo **TOutput**. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/). |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::DecoderFallback](../system.text/decoderfallback/). |
| [DecoderPtr](./decoderptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::Decoder](../system.text/decoder/). |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/). |
| [DirectoryInfoPtr](./directoryinfoptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::IO::DirectoryInfo](../system.io/directoryinfo/). |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/). |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::EncoderFallback](../system.text/encoderfallback/). |
| [EncoderPtr](./encoderptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::Encoder](../system.text/encoder/). |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/). |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/). |
| [EncodingInfoPtr](./encodinginfoptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::EncodingInfo](../system.text/encodinginfo/). |
| [EncodingPtr](./encodingptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::Text::Encoding](../system.text/encoding/). |
| [Event](./event/) | Representa un evento: un mecanismo mediante el cual los suscriptores son notificados sobre una ocurrencia de interés mediante la invocación de un delegado. |
| [EventArgsPtr](./eventargsptr/) | Puntero compartido a una instancia de la clase [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | Representa un método que reacciona y procesa un evento. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](./smartptr/) para gestionar objetos de este tipo. |
| [Exception](./exception/) | Alias que se debe usar en lugar de Details::Exception. |
| [ExceptionPtr](./exceptionptr/) | Alias de tipo usado por los contenedores de excepciones. |
| [FileInfoPtr](./fileinfoptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::IO::FileInfo](../system.io/fileinfo/). |
| [FileStreamPtr](./filestreamptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::IO::FileStream](../system.io/filestream/). |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Un alias para un smart pointer que apunta a una instancia de la clase [System::IO::FileSystemInfo](../system.io/filesysteminfo/). |
| [FunctionPtr](./functionptr/) | Un alias para un tipo de función con convención de llamada predeterminada. |
| [IAsyncResultPtr](./iasyncresultptr/) | Puntero compartido a [IAsyncResult](./iasyncresult/). |
| [IFormatProviderPtr](./iformatproviderptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::IFormatProvider](./iformatprovider/). |
| [MakeConstRef_t](./makeconstref_t/) | Tipo auxiliar para el modificador [MakeConstRef](./makeconstref/). |
| [MemoryStreamPtr](./memorystreamptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::IO::MemoryStream](../system.io/memorystream/). |
| [Predicate](./predicate/) | Representa un puntero a un predicado - una entidad invocable que acepta un solo argumento y devuelve un valor booleano. |
| [RTaskPtr](./rtaskptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/). |
| [SharedPtr](./sharedptr/) | Alias para un puntero inteligente ampliamente usado en la biblioteca. |
| [StreamPtr](./streamptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::IO::Stream](../system.io/stream/). |
| [StreamReaderPtr](./streamreaderptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::IO::StreamReader](../system.io/streamreader/). |
| [StreamWriterPtr](./streamwriterptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::IO::StreamWriter](../system.io/streamwriter/). |
| [StringComparerPtr](./stringcomparerptr/) | Un alias para un puntero compartido a una instancia de la clase [StringComparer](./stringcomparer/). |
| [SystemException](./systemexception/) |  |
| [TaskPtr](./taskptr/) | Un alias para un puntero inteligente que apunta a una instancia de la clase [System::Threading::Tasks::Task](../system.threading.tasks/task/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias para un puntero compartido a una instancia de la clase [TimeZoneInfo](./timezoneinfo/). |
| [TimeZonePtr](./timezoneptr/) | Puntero compartido a una instancia de la clase [TimeZone](./timezone/). |
## Functions

| Función | Descripción |
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
| BuildArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| Predeterminado | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Predeterminado | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Descartar | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EjecutarTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EjecutarTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EjecutarTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| Igual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Igual< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Igual< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConversiónExplícita | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForzarConversiónEstática | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ParaCadaMiembroGVNombre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GIgual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Obtener | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| obtener_puntero | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObtenerCódigoHash | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObtenerCódigoHash | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObtenerCódigoHash | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObtenerCódigoHash | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObtenerCódigoHash | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Mayor | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| InicializarObjeto | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Es | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Es | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Es | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| es_prueba_parametrizada | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| es_prueba_vp | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsEnumMetaInfoDefinida | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsEnumMetaInfoDefinida | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsInfinito | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsInfinitoNegativo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsNulo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsInfinitoPositivo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EsTupla | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterarSobre | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MenorIgual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Menor | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearArreglo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearArreglo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearArreglo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearObjeto | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearObjeto | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearGuardiaDeÁmbito | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearPunteroCompartido | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearPunteroCompartido | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearTupla | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearValorAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearValorAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearEnumerableConYield | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CrearEnumeradorConYield | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ClonarPorMiembros | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::ObtenerTipo< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::ObtenerTipo< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| operador* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| operador>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operador>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| Set | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
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
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
