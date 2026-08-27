---
title: "optimize"
second_title: "Aspose.PDF für Rust über C++"
description: "Optimiert den Inhalt des PDF-Dokuments."
type: docs
url: /de/rust-cpp/organize/optimize/
---

_Optimiert den Inhalt des PDF-Dokuments._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Optimieren Sie den Inhalt des PDF-Dokuments
    pdf.optimize()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```