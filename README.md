# Homicide-Stats-NY-NJ-CONN-PENN
### An interactive visualisation of Homicide Statistics in the states of New York, New Jersey, Connecticut, and Pennsylvania.

##### Dataset and Data Dictionary were retrieved from http://www.murderdata.org/p/data-docs.html and is entitled "The Supplementary Homicide Report".

<img width="812" alt="Screenshot 2021-08-20 at 12 34 53" src="https://user-images.githubusercontent.com/81429502/130227463-bf39683e-b3d1-4aff-85c4-bfd2255bbbf2.png">


#### The dataset was downloaded from the website and was inputted into RStudio. The RMD File was used. When the new file was created, the file was inputted into Tableau. A new calculated field would need to be added to the datafile. On the data source page, it is visible that for the variable “Weapon”, there are numerous weapons used that can be categorized together such as the different forms of shooting weapons. Therefore, the Weapon column was converted into a calculated field called “Weapons”, where "Firearm, type not stated", "Handgun - pistol, revolver, etc", Rifle", "Shotgun" and "Other gun" became Gun  Crime, "Asphyxiation - includes death by gas" was Asphyxiation, "Knife or cutting instrument" was Stabbing, “Fire” became Fire, and the rest became Other. Then this Tableau analysis was carried out. 
