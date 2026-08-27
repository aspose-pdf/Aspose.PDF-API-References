---
title: "Bytes"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt den Inhalt des PDF-Dokuments als Byte-Vektor zurück."
type: docs
url: /de/rust-cpp/core/bytes/
---

_Gibt den Inhalt des PDF-Dokuments als Byte-Vektor zurück._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Gib den Inhalt des PDF-Dokuments als Byte-Vektor zurück
    let data = pdf.bytes()?;

    // Länge des Byte-Vektors ausgeben
    println!("Length: {}", data.len());

    Ok(())
}

```