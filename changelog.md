#Change Log

Team membership:  
    - Terra Hunter <ms.terra.h@gmail.com>
    - Taryn Stickney

Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 


Release Date: Nov 18, 2017
## *Version 3.0*
### Description
    - Updated the store() function to use XML (Job 3) - Terra
    - Fixed a bug with create task. - Terra
    - Found a way to properly format XML files via DOM - Terra
### Updated components
    - core/XML_Model.php
        - Store function updated.
        - Minor fix to load function.
    

## *Version 2.5*
    - Created XML data (Job 1). -Taryn
    - Created XML_Model with load() (Job 2). -Taryn
### New Components
    - core/XML_Model.php
        - Created it, based off CSV_Model.php...
        - Changed the load function to work with XML.
### Updated Components
    - models/Tasks.php
        - Changed to extend XML_Model
    







Release Date: Oct 20, 2017
## *Version 2.0*
### Description
    - Polished the adding of tasks. (Job 11) - Taryn
### Updated components
    - controllers/Mtce.php
        - Added ability to save the task's status, size, and group.
    - views/itemedit.php
        - Added the fields to the form to update status, size and group of 
          new tasks. 

## *Version 1.4*
    - Added the ability to complete tasks (Job 8). -Taryn
### Updated Components
    - controllers/Views.php
        - check if the user is the task owner and allow them to view their tasks
        - update the task if it is marked completed
    - views/by_priority.php
        - Added a form to allow users to complete a task via checkbox.
        - Added checkbox items to the table.
    - core/Memory_Model.php
        - Corrected an error from the upstream repo.
    - README.md
        - Updated with the latest application info.

## *Version 1.3*
### Description
    - Job 7 done (Terra)
### Updated Components
    - constants.php
    - _menubar.php
    - .gitignore
    - config.php
    - autoload.php
    - Mtce.php
### New Components
    -  controller/Roles.php

## *Version 1.2*
### Description
    - Added pagination (Job 6) -Taryn
### Updated Components
    - controllers/Mtce.php
        - Added the ability to display a certain number of items per page.
    - views/itemlist.php
        - Added the pagination element.
### New Components
    - views/itemnav.php
        - Created the navigation for the pages.

## *Version 1.1*
### Description
    - Job 4 done (Terra)
### Updated Components
    - config.php (Terra)
### New Components
    - itemlist.php (Terra)
    - Mtce.php (Terra)
    - oneitem.php (Terra)






Release Date: Oct 12, 2017
## *Version 1.0*
### Description
    - Completed Job 5
### Updated components
    - config/config.php
        - Updated the Help Wanted menu link to display from the Helpme controller.
    - config/autoload.php
        - Added the Parsedown library to the autoload list.
### New Components
    - controllers/Helpme.php
        - Displays a request parsed from markdown.
    - data/jobs.md
        - A markdown file containing a request to be displayed.
    - libraries/Parsedown.php
        - Added a markdown parse library.

## *Version 0.4*
### Description
    - Completed Job 3
### Updated Components
    - controllers/MY_Controller
        - Edited so that the template is displayed properly
    - models/Tasks.php 
        - Added functionality to display a categorized list of tasks.
        - Added a sort function to sort tasks by category.
    -config/config.php
        - Updated the menu link Work to display from the Views controller.
### New Components
    - views/template_secondary.php
        - Created a template that displays the priority and category lists.
    - views/by_category.php
        - The content of the category list.
    - views/by_priority.php 
        - The content of the priority list.
    - controllers/Views.php
        - Displays the priority and category lists. 
        - Contains a function to sort tasks by priority.
        - Contains functionality to display the priority list. 

## *Version 0.3*
### Description
    - Completed Job 2
    - Fixed some issues in Job 1
### Updated Components
    - constants.php (Terra)
        - DATAPATH fixed.
    - public/index.php (Terra)
        - Returned the FCPATH definition because problems.
    - controller/Welcome.php (Terra)
        - Added functionality to display tasks
    - views/homepage.php
        - Added table to the page, that is controlled by the controller

## *Version 0.2*
### Description
    - Completed Job 1
### Updated Components
    - autoload.php (Terra)  
    - constants.php (Terra)
        - Defined the DATAPATH constant.
        - Defined the FCPATH constant.
    - public/index.php (Terra)
        - Removed the FCPATH definition.
### New Components
    -  models/Tasks.php (Terra)
        - basic model construction. 

## *Version 0.1*
### Description
    - Created changelog and formated it, ready for use.
### New Components
    -  changelog.md (Terra)





