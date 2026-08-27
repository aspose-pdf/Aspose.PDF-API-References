---
title: "Licença"
linktitle: "Licença"
second_title: "Referência da API Aspose.PDF para Java"
description: "Fornece métodos para licenciar o componente. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na."
type: docs
weight: 2670
url: /pt/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Fornece métodos para licenciar o componente. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic");

## Construtores

| Construtor | Descrição |
| --- | --- |
| [License](#License--) | Inicializa uma nova instância desta classe. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic"); |

## Métodos

| Método | Descrição |
| --- | --- |
| [clearLicense](#clearLicense--) | Limpa a licença atual. |
| [getLicenseInfo](#getLicenseInfo--) | Obtém as informações da licença atual. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Por padrão, estamos usando a segurança padrão do JDK. Valor padrão == false. Em alguns casos, o ambiente Java personalizado não pode suportar os algoritmos necessários, portanto podemos sugerir o uso da segurança interna incorporada FIPS. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Por padrão, estamos usando a segurança padrão do JRE. Valor padrão == false. Em alguns casos, o ambiente Java personalizado não pode suportar os algoritmos necessários, portanto podemos sugerir o uso da segurança interna incorporada FIPS. <p> Observe também: De acordo com o algoritmo SecureRandom da JVM, em alguns sistemas operacionais /dev/random aguarda que uma certa quantidade de “ruído” seja gerada na máquina host antes de retornar um resultado. A biblioteca usada para geração de números aleatórios na JVM da Oracle depende de /dev/random por padrão em plataformas UNIX. Embora /dev/random seja mais seguro, recomenda‑se usar /dev/urandom se a configuração padrão da JVM causar atrasos, ou adicionar dispositivos que gerem entropia para /dev/random. <p> A opção Java a seguir pode ajudar a evitar atrasos e sobrescrever a configuração securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licencia o componente. Um fluxo que contém a licença. Use este método para carregar uma licença a partir de um fluxo. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licencia o componente. Tenta encontrar a licença nos seguintes locais: 1. Caminho explícito. 2. A pasta do arquivo JAR do componente. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Inicializa uma nova instância desta classe. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Limpa a licença atual.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Obtém as informações da licença atual.

**Returns:**
Instância LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Por padrão, estamos usando a segurança padrão do JDK. Valor padrão == false. Em alguns casos, o ambiente Java personalizado não pode suportar os algoritmos necessários, portanto podemos sugerir o uso da segurança interna incorporada FIPS.

**Returns:**
valor booleano

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Por padrão, estamos usando a segurança padrão do JRE. Valor padrão == false. Em alguns casos, o ambiente Java personalizado não pode suportar os algoritmos necessários, portanto podemos sugerir o uso da segurança interna incorporada FIPS. <p> Observe também: De acordo com o algoritmo SecureRandom da JVM, em alguns sistemas operacionais /dev/random aguarda que uma certa quantidade de “ruído” seja gerada na máquina host antes de retornar um resultado. A biblioteca usada para geração de números aleatórios na JVM da Oracle depende de /dev/random por padrão em plataformas UNIX. Embora /dev/random seja mais seguro, recomenda‑se usar /dev/urandom se a configuração padrão da JVM causar atrasos, ou adicionar dispositivos que gerem entropia para /dev/random. <p> A opção Java a seguir pode ajudar a evitar atrasos e sobrescrever a configuração securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| internalFIPSSecurity |  | valor booleano |

### setLicense {#setLicense-java.io.InputStream-}
Licencia o componente. Um fluxo que contém a licença. Use este método para carregar uma licença a partir de um fluxo. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licencia o componente. Tenta encontrar a licença nos seguintes locais: 1. Caminho explícito. 2. A pasta do arquivo JAR do componente. Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. License license = new License(); license.setLicense("MyLicense.lic");
