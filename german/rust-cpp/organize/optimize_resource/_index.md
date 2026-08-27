---
title: "optimize_resource"
second_title: "Aspose.PDF für Rust über C++"
description: "Optimiert Ressourcen des PDF-Dokuments."
type: docs
url: /de/rust-cpp/organize/optimize_resource/
---

_Optimiert Ressourcen des PDF-Dokuments._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // Ressourcen des PDF-Dokuments optimieren
    pdf.optimize_resource()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```