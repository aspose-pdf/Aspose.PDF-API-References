---
title: "License"
linktitle: "License"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Proporciona métodos para licenciar el componente. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la."
type: docs
weight: 2670
url: /es/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Proporciona métodos para licenciar el componente. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic");

## Constructores

| Constructor | Descripción |
| --- | --- |
| [License](#License--) | Inicializa una nueva instancia de esta clase. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic"); |

## Métodos

| Método | Descripción |
| --- | --- |
| [clearLicense](#clearLicense--) | Borra la licencia actual. |
| [getLicenseInfo](#getLicenseInfo--) | Obtiene la información de la licencia actual. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Por defecto, estamos usando la seguridad predeterminada del jdk. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad interna incorporada FIPS. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Por defecto, estamos usando la seguridad predeterminada del jre. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad interna incorporada FIPS. <p> Observe también: Según el algoritmo SecureRandom de la JVM, en algunos sistemas operativos /dev/random espera a que se genere una cierta cantidad de “ruido” en la máquina host antes de devolver un resultado. La biblioteca utilizada para la generación de números aleatorios en la JVM de Oracle depende de /dev/random por defecto en plataformas UNIX. Aunque /dev/random es más seguro, se recomienda usar /dev/urandom si la configuración predeterminada de la JVM tiene retrasos, o añadir dispositivos que generen entropía para /dev/random. <p> La siguiente opción de java puede ayudar a evitar retrasos y sobrescribir la configuración securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licencia el componente. Un flujo que contiene la licencia. Use este método para cargar una licencia desde un flujo. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licencia el componente. Intenta encontrar la licencia en las siguientes ubicaciones: 1. Ruta explícita. 2. La carpeta del archivo jar del componente. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Inicializa una nueva instancia de esta clase. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Borra la licencia actual.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Obtiene la información de la licencia actual.

**Returns:**
Instancia de LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Por defecto, estamos usando la seguridad predeterminada del jdk. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad interna incorporada FIPS.

**Returns:**
valor booleano

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Por defecto, estamos usando la seguridad predeterminada del jre. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad interna incorporada FIPS. <p> Observe también: Según el algoritmo SecureRandom de la JVM, en algunos sistemas operativos /dev/random espera a que se genere una cierta cantidad de “ruido” en la máquina host antes de devolver un resultado. La biblioteca utilizada para la generación de números aleatorios en la JVM de Oracle depende de /dev/random por defecto en plataformas UNIX. Aunque /dev/random es más seguro, se recomienda usar /dev/urandom si la configuración predeterminada de la JVM tiene retrasos, o añadir dispositivos que generen entropía para /dev/random. <p> La siguiente opción de java puede ayudar a evitar retrasos y sobrescribir la configuración securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| internalFIPSSecurity |  | valor booleano |

### setLicense {#setLicense-java.io.InputStream-}
Licencia el componente. Un flujo que contiene la licencia. Use este método para cargar una licencia desde un flujo. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licencia el componente. Intenta encontrar la licencia en las siguientes ubicaciones: 1. Ruta explícita. 2. La carpeta del archivo jar del componente. En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. License license = new License(); license.setLicense("MyLicense.lic");
