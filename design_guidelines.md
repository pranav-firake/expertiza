# Design guidelines for expertiza UI



## Homepage (Danish)

For the Homepage we have only used one CSS class apart from native bootstrap and that is for crousel. However, this css class is not necessary for other pages unless you want to include a crousel on your page. 

To make a page similar to Homepage following steps can be followed.

* #### To add Crousel


   - Add an outer div `<div class="carousel slide" data-ride="carousel">`.
   + Inside this div you can define optional page indicators with `<ol>` Tag
   - After this to include the data or items in crousel use `<div class="carousel-inner" role="listbox">`.
   - Inside this div define individual items like `<div class="item">` 
   - To make an item active use `<div class="item active">`
   







## Header 
## logo

## Dropdown

## User Profile (sign in/out)

## Footer



## (Rui)

## Tables 

For the tables, we recommend using bootstrap table class to make tables looks unified. We already include bootstrap reference, feel free to reference that table styles. For react.js tables, we can still use [react-bootstrap-table](http://allenfang.github.io/react-bootstrap-table/) to make tables unified.


## (Pranav)

---

## Common Elements : 

**Element Name**
**Image**
**Usage**
**Guide**
**Code**	
|---|---|---|---|---|
|  1 |  Button - Red style | ![button](Design_Images/image5.png)  | Any button to be added. No need to add any class  | ```<button type="submit" class="btn btn-primary pull-right new-button">New public course</button> ``` |
|  2 |  Link -  | ![Link](Design_Images/image13.png)  |  Any link to be added on page. No need to add any class | ``` <a href="/student_task/view?id=2970"> MAE277 Group Project Report</a> ```  |
|  3 |  Circled numbers | ![Circled Number](Design_Images/image3.png)  |  Numbers that are to be styled in red circle, Kindly add class as badge | ``` <span class="badge">0</span> ```  |
|  4 |  Text Input | ![Text Input](Design_Images/image9.png)  | Any text input to be added on page. No need to add any class  |  ``` <input placeholder="Search..." value="" type="text"> ``` |

---
## Icon Library 

> Icons are available in 4 sizes : 16, 24, 32, 48 
> Edit the number as per size chose, everything else will remain same

**Element Name**
**Image**
**Usage**
**Guide**
**Code**	
|---|---|---|---|---|
|  1 |  Add assignment | ![Add Assignment](Design_Images/image4.png)  | To add 'add assignment' icon, use path **```/assets/tree_view/add-assignment-24.png```** | ```<img alt="" src="/assets/tree_view/add-assignment-24.png" > ``` |
|  2 |  Add Teaching assistant | ![Add TA](Design_Images/image16.png)  | To add 'add TA' icon, use path **```/assets/tree_view/add-ta-24.png```** | ```<img alt="" src="/assets/tree_view/add-ta-24.png" > ``` |
|  2 |  Add Private | ![Add Private](Design_Images/image18.png)  | To add 'add private' icon, use path **```/assets/tree_view/add-private-24.png```** | ```<img alt="" src="/assets/tree_view/add-private-24.png" > ``` |
|  2 |  Add Public | ![Add Public](Design_Images/image19.png)  | To add 'add public' icon, use path **```/assets/tree_view/add-public-24.png```** | ```<img alt="" src="/assets/tree_view/add-public-24.png" > ``` |
|  2 |  Add Signup Sheet | ![Add Signup sheet](Design_Images/image20.png)  | To add 'add signup sheet' icon, use path **```/assets/tree_view/add-signup-sheet-24.png```** | ```<img alt="" src="/assets/tree_view/add-signup-sheet-24.png" > ``` |
|  2 |  Assign Course Blue | ![Assign Course Blue](Design_Images/image21.png)  | To add 'Assign Course Blue' icon, use path **```/assets/tree_view/add-course-blue-24.png```** | ```<img alt="" src="/assets/tree_view/add-course-blue-24.png" > ``` |
|  2 |  Assign Course Green | ![Assign Course Green](Design_Images/image22.png)  | To add 'Assign Course Green' icon, use path **```/assets/tree_view/add-course-green-24.png```** | ```<img alt="" src="/assets/tree_view/add-course-green-24.png" > ``` |
|  3 |  Assign survey to | ![Assign survey to](Design_Images/image11.png)  | To add 'Assign survey to' icon, use path **```/assets/tree_view/assign-survey-24.png```** | ```<img alt="" src="/assets/tree_view/assign-survey-24.png" > ``` |
|  4 |  Copy | ![Copy](Design_Images/image1.png)  | To add "Copy" icon, use path **```/assets/tree_view/Copy-icon-24.png```** | ```<img alt="" src="/assets/tree_view/Copy-icon-24.png" > ``` |
|  5 |  Create Team | ![Create Team](Design_Images/image6.png)  | To add 'Create Team' icon, use path **```/assets/tree_view/create-teams-24.png```** | ```<img alt="" src="/assets/tree_view/create-teams-24.png" > ``` |
|  6 |  Delete | ![Delete](Design_Images/image15.png)  | To add "Delete" icon, use path **```/assets/tree_view/delete-icon-24.png```** | ```<img alt="" src="/assets/tree_view/delete-icon-24.png" > ``` |
|  7 |  (General) Edit | ![Edit](Design_Images/image14.png)  | To add "Edit" icon, use path **```/assets/tree_view/edit-icon-24.png```** | ```<img alt="" src="/assets/tree_view/edit-icon-24.png" > ``` |
|  7 |  Edit Signup sheet | ![Edit Signup sheet](Design_Images/image23.png)  | To add "Edit Signup sheet" icon, use path **```/assets/tree_view/edit-signup-sheet-24.png```** | ```<img alt="" src="/assets/tree_view/edit-signup-sheet-24.png" > ``` |
|  8 |  List All | ![List All](Design_Images/image8.png)  | To add "List All" icon, add class as "glyphicon glyphicon-list-alt" | ```<span class="glyphicon glyphicon-list-alt"></span> ``` |
|  7 |  List Submissions | ![List Submissions](Design_Images/image24.png)  | To add "List Submissions" icon, use path **```/assets/tree_view/List-submisstions-24.png```** | ```<img alt="" src="/assets/tree_view/List-submisstions-24.png" > ``` |
|  9 |  Make public from private | ![Make public from private](Design_Images/image10.png)  | To add "Make public from private" icon,  use path **```/assets/tree_view/lock-off-disabled-icon-24.png```**   | ```<img alt="" src="/assets/tree_view/lock-off-disabled-icon-24.png" > ``` |
|  9 |  Private | ![Private](Design_Images/image25.png)  | To add "Private" icon,  use path **```/assets/tree_view/lock-disabled-icon-24.png```**   | ```<img alt="" src="/assets/tree_view/lock-disabled-icon-24.png" > ``` |
|  9 |  Remove from Course | ![Remove from Course](Design_Images/image26.png)  | To add "Remove from Course" icon,  use path **```/assets/tree_view/remove-from-course-24.png```**   | ```<img alt="" src="/assets/tree_view/remove-from-course-24.png" > ``` |
|  9 |  Run Lottery | ![Run Lottery](Design_Images/image27.png)  | To add "Run Lottery" icon,  use path **```/assets/tree_view/run-lottery.png```**   | ```<img alt="" src="/assets/tree_view/run-lottery.png" > ``` |



## Special Elements in Inner Pages

