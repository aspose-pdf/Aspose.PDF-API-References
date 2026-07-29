---
title: "Licence"
linktitle: "Licence"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Fournit des méthodes pour licencier le composant. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le."
type: docs
weight: 2670
url: /fr/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Fournit des méthodes pour licencier le composant. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic");

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License](#License--) | Initialise une nouvelle instance de cette classe. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources intégrées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic"); |

## Méthodes

| Méthode | Description |
| --- | --- |
| [clearLicense](#clearLicense--) | Efface la licence actuelle. |
| [getLicenseInfo](#getLicenseInfo--) | Obtient les informations de la licence actuelle. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Par défaut, nous utilisons la sécurité jdk par défaut. Valeur par défaut == false. Dans certains cas, un environnement java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Par défaut, nous utilisons la sécurité jre par défaut. Valeur par défaut == false. Dans certains cas, un environnement java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée. <p> Note également : Selon l'algorithme JVM SecureRandom, sur certains systèmes d'exploitation /dev/random attend qu'une certaine quantité de « bruit » soit générée sur la machine hôte avant de renvoyer un résultat. La bibliothèque utilisée pour la génération de nombres aléatoires dans la JVM d'Oracle repose par défaut sur /dev/random pour les plates‑formes UNIX. Bien que /dev/random soit plus sécurisé, il est recommandé d'utiliser /dev/urandom si la configuration JVM par défaut entraîne des retards, ou d'ajouter des dispositifs qui génèrent de l'entropie pour /dev/random. <p> L'option java suivante peut aider à éviter les retards et à remplacer le paramètre securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licence le composant. Un flux contenant la licence. Utilisez cette méthode pour charger une licence depuis un flux. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licence le composant. Tente de trouver la licence aux emplacements suivants : 1. Chemin explicite. 2. Le dossier du fichier jar du composant. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources intégrées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Initialise une nouvelle instance de cette classe. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources intégrées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Efface la licence actuelle.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Obtient les informations de la licence actuelle.

**Returns:**
instance LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Par défaut, nous utilisons la sécurité jdk par défaut. Valeur par défaut == false. Dans certains cas, un environnement java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée.

**Returns:**
valeur booléenne

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Par défaut, nous utilisons la sécurité jre par défaut. Valeur par défaut == false. Dans certains cas, un environnement java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée. <p> Note également : Selon l'algorithme JVM SecureRandom, sur certains systèmes d'exploitation /dev/random attend qu'une certaine quantité de « bruit » soit générée sur la machine hôte avant de renvoyer un résultat. La bibliothèque utilisée pour la génération de nombres aléatoires dans la JVM d'Oracle repose par défaut sur /dev/random pour les plates‑formes UNIX. Bien que /dev/random soit plus sécurisé, il est recommandé d'utiliser /dev/urandom si la configuration JVM par défaut entraîne des retards, ou d'ajouter des dispositifs qui génèrent de l'entropie pour /dev/random. <p> L'option java suivante peut aider à éviter les retards et à remplacer le paramètre securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| internalFIPSSecurity |  | valeur booléenne |

### setLicense {#setLicense-java.io.InputStream-}
Licence le composant. Un flux contenant la licence. Utilisez cette méthode pour charger une licence depuis un flux. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licence le composant. Tente de trouver la licence aux emplacements suivants : 1. Chemin explicite. 2. Le dossier du fichier jar du composant. Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources intégrées de l'assembly appelant. License license = new License(); license.setLicense("MyLicense.lic");
