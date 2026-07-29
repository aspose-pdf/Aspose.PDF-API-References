---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som EMF."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som EMF.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](#EmfDevice-int-int-) | Initierar en ny instans av klassen {@code EmfDevice} med angivna bilddimensioner och standardupplösning för rasterbilden som skrivs till emf (=150) |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Konverterar sidan till emf och sparar den i utdataströmmen. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konverterar sidan till emf och sparar den i utdataströmmen. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Initierar en ny instans av klassen {@code EmfDevice} med angivna bilddimensioner och standardupplösning för rasterbilden som skrivs till emf (=150)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildens utskriftsbredd. |
| höjd |  | Bildens utskrifts‑höjd. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Initierar en ny instans av {@code EmfDevice} klassen med standardupplösning för rasterbild som skrivs till emf.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Konverterar sidan till emf och sparar den i utdataströmmen.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konverterar sidan till emf och sparar den i utdataströmmen.
