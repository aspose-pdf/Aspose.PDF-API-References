---
title: "Bytes"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le contenu du document PDF sous forme de tranche d'octets."
type: docs
url: /fr/go-cpp/core/bytes/
---

_Retourner le contenu du PDF-document sous forme de tranche d'octets._

```go
func (document *Document) Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **\[\]byte** - raw bytes of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
        "github.com/aspose-pdf/aspose-pdf-go-cpp"
        "log"
        "os"
)

func main() {
        // New crée un nouveau PDF-document
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes renvoie le contenu du PDF-document sous forme de tranche d'octets
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Enregistrer la tranche d'octets dans un fichier.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
