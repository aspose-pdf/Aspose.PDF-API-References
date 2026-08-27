---
title: "Bytes"
second_title: "Aspose.PDF für Go über C++"
description: "Den Inhalt des PDF-Dokuments als Byte-Array zurückgeben."
type: docs
url: /de/go-cpp/core/bytes/
---

_Gibt den Inhalt des PDF-Dokuments als Byte-Array zurück._

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
        // New erstellt ein neues PDF-Dokument
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes gibt den Inhalt des PDF-Dokuments als Byte-Array zurück
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Speichert das Byte-Array in einer Datei.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
