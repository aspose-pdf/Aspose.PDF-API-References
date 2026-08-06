---
title: "export_xfdf"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Esporta dal PDF-document precedentemente aperto con AcroForm in XFDF-document con nome file."
type: docs
url: /it/rust-cpp/convert/export_xfdf/
---

_Esporta dal PDF-document precedentemente aperto con AcroForm in XFDF-document con nome file._

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Esporta dal PDF-document precedentemente aperto con AcroForm in XFDF-document
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```