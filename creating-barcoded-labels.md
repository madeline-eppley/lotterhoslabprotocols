# Creating barcoded labels

*note - TSC printer is in the shared equipment lab, hooked up to the Plate Reader laptop.*

1.	Create an excel spreadsheet with the sample IDs for your labels. Type “ID” on cell A1 and list your label IDs on the following rows (you can use more than one column). Save this document and CLOSE IT before you move on to the next step.

2.	Check that the printer is on – green light on top of the printer. Launch the software BarTender Designer (a shortcut should be pinned to the taskbar).

3.	In the welcome screen, ‘Open a recently used BarTender document’ or ‘Open an existing BarTender document’. 

     *a.	If you accidentally close the welcome screen, go to File > New > New Document Wizard > Existing BarTender Document > Select > Select a template document > Open > Finish (not Next).*

     *b.	This will define the printer model (we only have one) and the type of stock label (we only have one) so you do not need to enter these paramenters manually (saves time).*

4.	File > Save as  > ‘yourfilename’.

5.	On the document you just created (‘yourfilename’), click on the barcode on the screen and delete it, so you have a blank label. 

6.	Create > Barcode > code 93 > then click anywhere on the label to place the barcode.
  
      *a.	This will place a barcode on the label on the screen. Roughly adjust the size of the barcode to fit the label.*
      
7.	On the left side panel, right-click on Database Fields > Database Connection Setup > Configure Connection > Browse and select the Excel file with your sample IDs > Finish (not Next) > Ok.
  
      *a.	If the window “The format of the database in ‘yourexcelfile’ does not match the old database” pops up, click yes. Then click to highlight Sheet$1 and hit Finish.*
      
      *b.	This will add your sample ID next to the barcode on the label.*

8.	On the left side panel, click on ‘Barcode’ to highlight it. Then go to Edit > Properties.

9.	Under Human Readable > Placement, select “Right” (this is recommended because of the shape of labels we currently have; if using another label, edit barcode placement and sample ID placement accordingly). Horizontal offset: “0.03” is recommended, but will depend on the length of the barcode and sample ID. 
  
      *a.	Optional: Symbology and Size: the type, size and placement of the barcode on the label can be edited here, if needed.*
  
      *b.	Optional: Font, Text Format, Border and Position can be edited here, if needed.*

10.	Under Datasource, right-click the embedded data (should appear as 12345678), and delete.

11.	If you see 12345678 instead of you sample ID on the label, go to Data Source (left panel), right-click the embedded data (12345678), and hit delete. Right-click on Data Source > New > Database field > Next > Select field name (“ID”, or whatever else is in the first row of you excel file) and delete whatever is in ‘Sample Field Data’ > Finish. 
  
      *a.	This should show the first sample ID next to the barcode on the label. You might need to edit font size to fit the label. (Don’t exit barcode properties). In Font, select the appropriate size under Point Size > Close.*

12.	Re-size the barcode and sample ID within the margins of the label if necessary, by adjusting the barcode window on the label and/or editing barcode properties until your label looks the way you want (keep in mind the labels are small so try to maximize font size to fill out most of the label).
  
13. At the bottom of the screen, you should see the number of labels you are creating – this number should match the rows on the excel file (minus 1, the A1 cell labeled "ID"). Use the arrows to scroll through the labels and make sure they all fit within the margins of the labels. Adjust accordingly, if needed.

14.	Hit Print on top of the page or File > Print. It is recommended to print the first ~5 labels first to see how the come out. To do that, select “Selected” under “Queried Records” and type 1-5 in “Selected Records”. If looks ok, print the rest. If barcodes and sample IDs do not fit on the printed label, go back to Properties > Edit (steps 8-9). If you want to print all at once, select “All” under “Queried Records”. 

15.	Cut off your labels from the printer, close document, close software.
