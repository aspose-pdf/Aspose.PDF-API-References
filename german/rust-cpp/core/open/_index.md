---
title: "open"
second_title: "Aspose.PDF für Rust über C++"
description: "Öffnet ein PDF-Dokument mit Dateinamen."
type: docs
url: /de/rust-cpp/core/open/
---

_Öffnet ein PDF-Dokument mit Dateinamen._

```rust
pub fn open(filename: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document mit dem Namen "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_open.pdf")?;

    Ok(())
}

```