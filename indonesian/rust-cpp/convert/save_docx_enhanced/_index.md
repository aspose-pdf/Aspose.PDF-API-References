---
title: "save_docx_enhanced"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan dokumen PDF yang sebelumnya dibuka sebagai DOCX-document dengan Enhanced Recognition Mode (tabel dan paragraf yang dapat diedit sepenuhnya)."
type: docs
url: /id/rust-cpp/convert/save_docx_enhanced/
---

_Mengonversi dan menyimpan dokumen PDF yang sebelumnya dibuka sebagai DOCX-document dengan Enhanced Recognition Mode (tabel dan paragraf yang dapat diedit sepenuhnya)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
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

    // Konversi dan simpan dokumen PDF yang sebelumnya dibuka sebagai DocX-document dengan Enhanced Recognition Mode (tabel dan paragraf yang dapat diedit sepenuhnya)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```