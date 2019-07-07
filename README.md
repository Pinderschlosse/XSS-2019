# Refactoring documentation of the [Foliant][productrep] application

<!-- TOC -->

- [Refactoring documentation of the [Foliant][productrep] application](#refactoring-documentation-of-the-foliantproductrep-application)
  - [Glossary](#glossary)
  - [Investigate the [application](https://github.com/foliant-docs/foliant)](#investigate-the-applicationhttpsgithubcomfoliant-docsfoliant)
    - [Steps:](#steps)
  - [Start refactoring the [documentation][foliantdocs]](#start-refactoring-the-documentationfoliantdocs)
    - [Steps:](#steps-1)
  - [The 'Done' table](#the-done-table)

<!-- /TOC -->
---

### Glossary

- **Application** - here and further: product called Foliant, located in this [repository][productrep] only
- **Documentation** - here and further: all information about the **application**, contains in [README.md][productrep] file and on [Foliant Main Documentation][foliantdocs] page
- **TOC** - Table of Contents

<pre style="font-size: 80%; background-color: #c7e3ff"><strong>Tip:</strong> following next steps will increase your workflow efficiency. Maybe</pre>

### Investigate the [application](https://github.com/foliant-docs/foliant)

##### Steps:

1. Go to [https://github.com/foliant-docs/foliant][productrep]
2. Read and follow instructions in **README.md** file
    + if you don't know how to download and install Python 3.xx - <s>what are you doing here?</s> go to [BeginnersGuide/Download](https://wiki.python.org/moin/BeginnersGuide/Download) section on [Python](https://www.python.org) official site
3. Note any inconsistencies: mistakes, syntax, differences between actual and expected results in the installation process, etc. Need to find as much as possilbe!
    + <pre style="font-size: 80%; background-color: #c7e3ff"><strong>Tip:</strong> lecture #2 from Xsolla Summer School'19 can be a great help in this</pre>
4. Fix all founded inconsistencies with any convenient tools
5. Push final result in [repository][reportrep] on GitHub
    + <pre style="font-size: 80%; background-color: #ffc7c7"><strong>Attention:</strong> need to define names and structure of the directories before ```push``` all changes</pre>

### Start refactoring the [documentation][foliantdocs]

##### Steps:

1. Go to [Foliant Main Documentation][foliantdocs] page
2. Note any inconsistencies on the current page: mistakes, syntax, differences between actual and expected results in discribed processes, etc. Need to find as much as possilbe!
    + <pre style="font-size: 80%; background-color: #c7e3ff"><strong>Tip:</strong> lecture #2 from Xsolla Summer School'19 can be a great help in this</pre>
3. Fix all founded inconsistencies with any convenient tools
4. Push final result in [repository][reportrep] on GitHub
    + <pre style="font-size: 80%; background-color: #ffc7c7"><strong>Attention:</strong> need to define names and structure of the directories before ```push``` all changes</pre>
5. Go to the next section of the Table Of Content <l style="color: #ff0000">(on the left upper part of the page, not the right upper!)</l>
6. Return to Step 2


### The 'Done' table

 >Use the table below to visually determine how much you've done.

 **Section of TOC**|**In Progress**|**Tested**|**Pushed**|**Accepted**
:------------------|:-------------:|:--------:|:--------:|:-----------:
Welcome to Foliant!|<l style="color: #72ff26">YES</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
Installation       |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
Quickstart         |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
Backends           |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
Preprocessors      |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
CLI Extentions     |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>
Config Extentions  |<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>|<l style="color: #ff0000">NO</l>





[productrep]: https://github.com/foliant-docs/foliant "Foliant repository"
[reportrep]: https://github.com/Pinderschlosse/XSS-19-Test-Task-1.git "Pinderschlosse's reporting repository"
[foliantdocs]: https://foliant-docs.github.io/docs/ "Foliant Main Documentation"
