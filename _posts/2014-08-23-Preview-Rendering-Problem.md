---
 layout: post
---

Recently, I am writing a paper to submit in the conference. I use a mac. Of course, I am using the default pdf reader - preview for my reading and presenting of my paper. The pdf of my pdf was generated by pdfLatex. The log message of the pdfLatex said warning messages about multiple pdfs are rendered in one page.I googled this warning message as I have a problem for preview rendering. Everytime I open my paper pdf, preview will not be active, especially when I try to slide the page. I fixed this by replacing all the 
pdf figures in my paper pdf with the following command 
>pdf2ps
>ps2pdf



