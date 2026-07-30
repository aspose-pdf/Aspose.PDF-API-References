---
title: "License.SetLicense"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode License. Licence le composant"
type: docs
weight: 40
url: /fr/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licenseName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | String | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

## Remarques

Essaie de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier qui contient l'assembly du composant Aspose.

3. Le dossier qui contient l'assembly appelant du client.

4. Le dossier qui contient l'assembly d'entrée (démarrage).

5. Une ressource incorporée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource incorporée dans l'assembly appelant du client.

[Java]

2. Le dossier qui contient le fichier JAR du composant Aspose.

3. Le dossier qui contient le fichier JAR appelant du client.

### Voir aussi

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Un flux qui contient la licence. |

## Remarques

Utilisez cette méthode pour charger une licence depuis un flux.

### Voir aussi

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


