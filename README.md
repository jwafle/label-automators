# stockx-label-automator
MacOS automator script to autocrop and print StockX labels from PDF format.
Dependencies: ImageMagick - can be downloaded using HomeBrew
Usage: Download the workflow file from the repository and place it in the /Macintosh HD/Users/your_user_here/Library/Services folder. Then navigate to the pdf file of interested and use the quick action to execute the workflow.
How it works: Grabs selected file from Finder. Converts from PDF to JPG. Automatically crops each page to relevant size. Rotates pages to print on thermal printer. Sends print job to printer.
