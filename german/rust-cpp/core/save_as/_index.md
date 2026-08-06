---
title: "save_as"
second_title: "Aspose.PDF für Rust über C++"
description: "Speichert das zuvor geöffnete PDF-Dokument mit einem neuen Dateinamen."
type: docs
url: /de/rust-cpp/core/save_as/
---

_Speichert das zuvor geöffnete PDF-Dokument mit einem neuen Dateinamen._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Speichere das PDF-Dokument mit neuem Dateinamen
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```