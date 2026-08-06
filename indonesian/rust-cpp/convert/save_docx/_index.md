---
title: "save_docx"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai dokumen DOCX-document."
type: docs
url: /id/rust-cpp/convert/save_docx/
---

_Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai dokumen DOCX-document._

```rust
pub fn save_docx(&self, filename: &str) -> Result<(), PdfError>
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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai dokumen DocX-document
    pdf.save_docx("sample.docx")?;

    Ok(())
}

```