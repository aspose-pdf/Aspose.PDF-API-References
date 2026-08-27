---
title: "neu"
second_title: "Aspose.PDF für Rust über C++"
description: "Erstellt ein neues PDF-Dokument."
type: docs
url: /de/rust-cpp/core/new/
---

_Erstellt ein neues PDF-Dokument._

```rust
pub fn new() -> Result<Self, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_new.pdf")?;

    Ok(())
}

```