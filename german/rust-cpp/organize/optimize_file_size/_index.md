---
title: "optimize_file_size"
second_title: "Aspose.PDF für Rust über C++"
description: "Optimiert die Größe eines PDF-Dokuments mit Bildkomprimierungsqualität."
type: docs
url: /de/rust-cpp/organize/optimize_file_size/
---

_Optimiert die Größe eines PDF-Dokuments mit Bildkomprimierungsqualität._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Optimieren Sie die Größe eines PDF-Dokuments mit Bildkomprimierungsqualität
    pdf.optimize_file_size(50)?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```