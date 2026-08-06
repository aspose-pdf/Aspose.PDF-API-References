---
title: "split_document"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Kaynak PDF-document'ten sayfalar çıkararak birden fazla yeni PDF-document oluşturur."
type: docs
url: /tr/rust-cpp/core/split_document/
---

_Kaynak PDF-document'ten sayfalar çıkararak birden fazla yeni PDF-document oluşturur._

```rust
pub fn split_document(document: &Document, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf" adlı bir PDF-document aç
    let pdf_split = Document::open("sample.pdf")?;

    // Kaynak PDF-document'ten sayfalar çıkararak birden fazla yeni PDF-document oluşturur
    let pdf_parts = Document::split_document(&pdf_split, "1;2-")?;

    // Her bölünmüş parçayı ayrı bir PDF-document olarak kaydet
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_document_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```