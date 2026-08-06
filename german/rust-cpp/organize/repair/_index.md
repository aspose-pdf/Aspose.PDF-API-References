---
title: "repair"
second_title: "Aspose.PDF für Rust über C++"
description: "Repariert das PDF-Dokument."
type: docs
url: /de/rust-cpp/organize/repair/
---

_Repariert das PDF-Dokument._

```rust
pub fn repair(&self) -> Result<(), PdfError>
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

    // PDF-Dokument reparieren
    pdf.repair()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```