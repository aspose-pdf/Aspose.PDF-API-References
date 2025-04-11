---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Méthode de licence. Licence le composant
type: docs
weight: 20
url: /fr/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licenseName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | String | Peut être un nom de fichier complet ou court ou le nom d'une ressource intégrée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

## Remarques

Essaye de trouver la licence dans les emplacements suivants :

1. Chemin explicite.

2. Le dossier qui contient l'assemblage du composant Aspose.

3. Le dossier qui contient l'assemblage appelant du client.

4. Le dossier qui contient l'assemblage d'entrée (de démarrage).

5. Une ressource intégrée dans l'assemblage appelant du client.

**Remarque :** Sur le .NET Compact Framework, essaie de trouver la licence uniquement dans ces emplacements :

1. Chemin explicite.

2. Une ressource intégrée dans l'assemblage appelant du client.

[Java]

2. Le dossier qui contient le fichier JAR du composant Aspose.

3. Le dossier qui contient le fichier JAR appelant du client.

### Voir aussi

* classe [License](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assemblage [Aspose.PDF](../../../)

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

Utilisez cette méthode pour charger une licence à partir d'un flux.

### Voir aussi

* classe [License](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assemblage [Aspose.PDF](../../../)