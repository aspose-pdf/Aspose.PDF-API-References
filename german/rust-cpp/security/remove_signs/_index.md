---
title: "remove_signs"
second_title: "Aspose.PDF für Rust über C++"
description: "Entferne Signaturen vom PDF-Dokument."
type: docs
url: /de/rust-cpp/security/remove_signs/
---

_Entfernen von Signaturen aus dem PDF-Dokument._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffnen Sie ein PDF-Dokument mit dem Namen "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Entfernen von Signaturen aus dem PDF-Dokument
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```