---
title: "flatten"
second_title: "Aspose.PDF für Rust über C++"
description: "Flacht das PDF-Dokument ab."
type: docs
url: /de/rust-cpp/organize/flatten/
---

_Flacht das PDF-Dokument ab._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
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