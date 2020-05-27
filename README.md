# The Asian American CV19 Archive Project: GitHub Data Repository
The github repository for www.asianamericancv19archiveproject.org is divided into the following folders:

<ul>
  <li><b>datafiles</b>: This directory contains the main index JSON file of all content data that is currently being archived.</li>  
  <li><b>images</b>: This directory holds all images that have been able to be archived.</li>  
  <li><b>htmlfiles</b>: This directory contains all source data that was able to be archived as HTML files.</li>  
  <li><b>pdfs</b>: This directory holds all source data that was able to be archived as PDF files.</li>  
</ul>

<b>Format of JSON entries</b>

The format of entries all follow the same format as the example below:

```json
{
    "Title": "Asian man waiting for NYC subway spit on, threatened in coronavirus hate crime",
    "Url": "https://www.nydailynews.com/coronavirus/ny-coronavirus-hate-crime-brooklyn-subway-spit-20200325-h4w4nzb74fbadpx6li4f7xdoc4-story.html",
    "ImgUrl": "89e6033e-c1e5-4dbc-a03d-39a0e42666da.jpg",
    "SiteName": "Daily News",
    "ArticleDate": "2020-03-25T05:00:00Z",
    "HTMLArchiveFileName": "eee15083-68ea-4d46-9f1c-2641a94e1f15.html",
    "PDFArchiveFileName": "eee15083-68ea-4d46-9f1c-2641a94e1f15.html.pdf"
  }
```
ImgUrl, HTMLArchiveFileName, and PDFArchiveFileName, do not have names which correspond to the content data titles or urls, and are generated with random GUID names, however the HTML and PDF archive file names relate to each other in that they each contain the same GUID in their name, however the PDF is simply named with a ".pdf" extenstion.

<b>External Files</b>

Any assets like images or their HTML and PDF archives, are all stored in their respective directories, however, they not all data content contains images, or was able to be archived as a HTML or PDF document.
