## My Lenovo Internship
### Vicki Shaw
### Summer 2017

#HSLIDE

### Projects
- Data Center Group Server Troubleshooting
- Asset Inventory Management System - AIMS 2.0

#HSLIDE

### DCG
*Goal:* Predict server failures before they happen

- Delay in approved access for private customer information
- Insufficient training data for machine learning algorithms
- Palantir partnership was not helpful for project's goal 
- Project terminated early

#HSLIDE

### AIMS 2.0
*Goal:* Redesign and implement product engineering lab inventory management system and application

Technologies used:
- C# winforms, Visual Studio
- DevExpress
- Entity Framework 6
- MySQL database
- Dymo Label Printer SDK

#HSLIDE

### AIMS 2.0 - Features
- Navigate through items in your queue, or all items
- Open tabs with more details of selected items
- Add multiple items at a time
- Edit existing items
- Ship items
- Scrap items
- Print item barcodes

#VSLIDE
![nav](assets/Navigation.gif)
#### Navigation
#VSLIDE
![add](assets/Add New.gif)
#### Adding Items
#VSLIDE
![edit](assets/Edit.gif)
#### Editing Items
#VSLIDE
![check](assets/CheckIn_Out_Search.gif)
#### Checking Items to Your Queue
#VSLIDE
![ship](assets/Ship.gif)
#### Shipping Items
#VSLIDE
![scrap](assets/Scrap.gif)
#### Scrapping Items
#VSLIDE
![admin](assets/Admin.gif)
#### Administrators, and Ron


#HSLIDE

# What's Next?

#VSLIDE

Documentation

    /// <summary> 
    /// Event handler for finish button click for add-new-item mode 
    /// </summary> 
    /// <param name="sender"></param> 
    /// <param name="e"></param> 

    private void bbi_add_finish_ItemClick(object sender, ItemClickEventArgs e) 
    { 
        //close UC 
    
        foreach (Control c in Controls.Find(UC_LABEL, false)) 
        { 
            Controls.Remove(c); 
        } 
    
        xtraTab_entries.Visible = true;  
    
        //close add ribbon page 
    
        ribbon_add.Visible = false; 
    
        //move user to home page 
        
        dockPanel.Visibility = DevExpress.XtraBars.Docking.DockVisibility.Visible; 
        ribbonPage_home.Visible = true; 
        ribbonControl.SelectedPage = ribbonPage_home;
    }
#VSLIDE

#### What I would do differently
- Ask more questions about users
- Design for modularity - less repeated code
- Version control

#VSLIDE

###AIMS 2.2?
- Beautification
- Flex database integration
- Increased admin functionality
- Advanced searching 
- RFID login and printing 

#HSLIDE

###Learnings
- Relational databases
- C# language
- VBA
- Powershell Script

#HSLIDE 

### "Do something you don't dislike"

#HSLIDE 

##Thank You
####Vicki Shaw 
####8.2.2017


