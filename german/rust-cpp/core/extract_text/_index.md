---
title: "extract_text"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt den Inhalt des PDF-Dokuments als Klartext zurück."
type: docs
url: /de/rust-cpp/core/extract_text/
---

_Gibt den Inhalt des PDF-Dokuments als Klartext zurück._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Gib den Inhalt des PDF-Dokuments als Klartext zurück
    let txt = pdf.extract_text()?;

    // Extrahierten Text ausgeben
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```