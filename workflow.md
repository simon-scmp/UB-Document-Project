### Workflow for Documents project

### Workflow so far…

1. Take initial Excel sheet with base data.
2. Duplicate the **Dates** column and convert to correctly formatted `00/00/2000` format (NB. The initial sheet was set to Armenian format not UK.) Index number column A needs also to be in *Number* format.
3. Convert the sheet to **Table Format** (I was unable to sort the dates on Excel but worked fine in Google Sheets).
4. Imported the data into new Google Sheet document (also version in there in Excel format  for Google sheets).
5. Shared for web from Sheets file (check auto update), hid column B for contributors names. [Link to sheets file](https://docs.google.com/spreadsheets/d/11zjqmcYhxKcK4aE7gL6R7wT0ZYlthhYtvYY5m7eTyRE/edit?usp=sharing)
6. Uploaded folder of images (032 bundle) to Google Drive NB for all this I’ve been logging in to the generic Upper Broughton Google Drive. Created new album in *Photos.Google.com* using the images from the drive and named accordingly. [Created link to the Album](https://photos.app.goo.gl/XcEALEC8tbh18hnu8)
7. Set up new **GitHub Pages** Repo to host the base web page. This is at: https://simon-scmp.github.io/ubhistdocs/ the Repo is: simon-scmp/ubhistdocs 
	1. There is another repo connected to this site for the documentation called: Simon-SCMP/UB-Document-Project this hosts this document initially.
8. Using instructions on [GitHub Pages](https://pages.github.com/) I set up new local directory on MBP in **Git** folder called `Git/UB_HistDoc_test/` Then using the instructions above did an initial commit and it worked.
9. Because of issues with version of **Jekyll and Ruby** on my MBP I cloned an existing, working Jekyll test folder set locally into the new project folder on the MBP and edited the files accordingly, removing the initial commit of the `index.html` replacing with `index.md` in the cloned directory, this all worked fine.
	1. The source files for the GH pages files are worked on locally and pushed to GH Pages Repo using either command line or BBEdit or VS Code which will do the commit from within the app.
	2. The commands required are: 
	3. > `Git add --all + git commit -m "comments here" + git push -u origin main`
	5. Terminal needs to be cd’d into the Git working folder for the project.
10. The GH Pages files links to the external Google Sheets and Google Photos files.
11. **Issues** when going to any of the Google pages it wants you to either log in or download their apps for Sheets or Photos which is a pain.
12. Can’t at the moment sort the database, it will sort but takes the header line and puts that elsewhere, I can freeze everything else but not the top row. Tables are not supported in Sheets. There is no link to go back to the host site and search not that good.
13. There could be the option to download the original files be they Excel or Sheets but may need vetting of users to do that and some sort of version numbering.