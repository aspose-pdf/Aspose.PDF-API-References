---
title: "merge_documents"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membuat PDF-document baru dengan menggabungkan PDF-document yang disediakan."
type: docs
url: /id/rust-cpp/core/merge_documents/
---

_Membuat PDF-document baru dengan menggabungkan PDF-document yang disediakan._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buat dokumen PDF baru
    let pdf1 = Document::new()?;

    // Buka PDF-document bernama "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Buat PDF-document baru dengan menggabungkan PDF-document yang disediakan
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```