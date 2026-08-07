# CAUL Open Access Title List
A searchable, filterable journal title list showing Read & Publish Agreement eligibility for CAUL member institutions. Built for researchers and librarians to quickly find which journals they can publish open access in with the APC covered or at a discounted APC fee.

### What is this?
This tool helps researchers at CAUL member institutions find journals covered by their institution's CAUL Read & Publish Agreements. By selecting your institution, you can immediately see:
* Which journals offer a full APC Waiver (publish open access with the APC fee covered)
* Which journals offer an APC Discount
* Which journals have no OA coverage under your agreement

### Using the title list
1. Go to the title list
2. Select your institution from the dropdown
3. Use the filters to narrow down your journal selections. The multi search filter allows you to search through any of the fields including journal title, ISSN, field of research, publisher
4. Click on any journal card to see more information and your institution's entitlements

### Data
Journal information is maintained by CAUL and updated in the excel spreadsheet under the 'Source' folder. 
This data is then converted to a JSON file using a python script in the 'Scripts' folder.
The widget uses the data in the JSON as the data source. When this is updated, the data in the widget will automatically update.

### For Institutions
The title list widget is free to use and placed in any location at your convenience. The code is HTML and can be embedded with no technical experience required. 
You can download the widget file directly from this repository:
1. Navigate to Widget/caul_title_list_widget.html
2. Click the file to open it
3. Click the 'Download Raw File' button (the download icon in the top right).
4. Open the file directly from your computer or embed the code wherever suits you.

You are welcome to modify the widget as you wish (colours, fonts, layout). As long as the 'DATA_URL' variable remains the same, the data will match any updates CAUL makes to the underlying data.

### Contact
For questions about agreements, eligibility, or to request updates to the list for any issues you notice, please contact consortium@caul.edu.au.

