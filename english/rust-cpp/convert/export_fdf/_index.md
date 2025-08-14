---
title: "export_fdf"
second_title: Aspose.PDF for Rust via C++
description: "Exports from previously opened PDF-document with AcroForm to FDF-document with filename."
type: docs
url: /rust-cpp/convert/export_fdf/
---

_Exports from previously opened PDF-document with AcroForm to FDF-document with filename._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
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
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Export from the previously opened PDF-document with AcroForm to FDF-document
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```