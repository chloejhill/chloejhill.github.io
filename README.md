CHLOE J HILL: MY PERSONAL WEBSITE
=================================

This is a ChloeJHill's web documentation.

## The main sections

There are 8 sections:

* **Header** section
* **Hello** section
* **Do** section
* **Love** section
* **Work** section
* **Clients** section
* **Journey** section
* **Contact** section

Each section starts with

```
<!-- BEGIN NAME SECTION -->

```

and ends with

```
<!-- END NAME SECTION -->

```

Inside those lines you can find all HTML code to build the section (images, headings, paragraphs, etc.)


## Edit contents

All content is on *index.html* so you navigate to this file and then press *edit this file* button. It appears a text editor in which you can find and replace the content you want to modify. Remember that all HTML keywords must not be modified (or at least you have to be carefull with that).

Once you have to modify some texts, the next step is to save changes. On GitHub the way to save changes is pressing *Commit chnages* button. This button can be found on the bottom of the edit page.


## Adding images

If you want to add new images, you have to navigate to *images* folder. Once you are on it, just press *Upload files* button. Select all files you want to upload from your local directory and the press *Commit changes* button (same action as below).

The next step is to import this file into *index.html* file. For that purpose, the best way is to copy an *<img>* tag from the page and replace the name odf the image file.

For example, if you copy *<img src="images/cover.jpg" alt="Chloe J Hill" class="img-fluid">*, this line with the new file could be *<img src="images/newfilename.jpg" alt="New name" class="img-fluid">*


## Adding new info blocks

This is the same actions as *Adding images*. If you want to add new info block, the best and easy way to do this is to copy the entire HTML block and replace the content you wish.

For example, if you want to add a new *DO item* on *DO section* copy

```
<div class="col-md-6 col-lg-3">
  <div class="illustration"><img src="images/icon1-challenge.png" alt="Challenge"></div>
  <h2>Dig Deep: Understanding the challenge</h2>
  <ul class="do-list">
    <li>Scope and scan</li>
    <li>Research  - audience mapping, interviews, personal observations, document analyses, future thinking/forecasting etc</li>
    <li>Diagnostics and establishing needs and priorities</li>
  </ul>
</div>
```

and replace the content you wish.


## Additional notes

All HTML code is full of start-end comments text. It must be very intuitive to add or modify new content. In case you need more help, please contact with the site administrator.
