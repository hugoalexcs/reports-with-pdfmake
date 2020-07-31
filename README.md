PDFMake comes with inbuilt methods :

Download the PDF : pdfMake.createPdf(docDefinition).download();
Open the PDF in new window : pdfMake.createPdf(docDefinition).open(); 
Open PDF in same window : pdfMake.createPdf(docDefinition).open({}, window);
Print the PDF: pdfMake.createPdf(docDefinition).print();

