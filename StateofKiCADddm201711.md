This Document defines the authors view of Kicad in context of a complete Electronic Design Data Management processes and requirements

# Analysis of Schematic Workflow with proposals for this KiCADddm suite.

| ACTION | TEST | STEPS and observations | Screen Shots|
|--------------------------------|------------------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Adding a new Part to Schematic | Does Part already exist in Kicad Library | kicad library , well curated, growing but limited, Fantastic that content is managed in a KiCAD GIT repository  | Example of Adding a part to the schematic from the Kicad Library![](https://github.com/auphofBSF/KiCadDDM/blob/master/media/image1.png) / |
|  |  |  TODO: <ul><li>Part Research,</li><li>Part Analysis (Cost, Engineering)</li><li>Part Data Curate</li><li>Part Inventory Management (Life cycle )</li><li></li></ul>   DONE: <ul><li>Part Symbol maintenance</li><li>Part Footprint Maintenance</li></ul> |
|  | Part Not in Kicad Library |  MANUAL STEPS REQUIRED:               
| | | <ul><li>Part Research</li><li>Part Analysis (Cost, Engineering) </li><li>Part Schematic Symbol and Footprint (Draw, Aquire) place in Organization Library, Part Footprint</li><li>  ----  If New part drawn: share to Kicad Library Repository </li><li>Part Data Curate </li><li>Part Inventory Management (Life cycle )</li><li></li><li></li> </ul>|                                                                          Assorted Tools plenty of adhoc manual processs                           BOMscripts , Spreadsheets, Boms-away, Kipartman   MRP ……..        usually post schematic capture lots of bom management and trying to capture bom details in schematic  
| Editing the value or footprint of a part in Schematic | Does Part already exist in Kicad Library | Manual Steps and Lookups on multiple systems   | "Example of Editing the value or parameters of a part in the schematic from the Kicad EESCHEMA" ![](https://github.com/auphofBSF/KiCadDDM/blob/master/media/kicadEeschemaComponentProperties.png)  |

---
# What KiCADddm looks like (Proposed)
---
Would be great if the status of parts in our inventory could be listed plus access a tools for component  
management (Such as KIPARTMAN ) and our MRP system (such as Odoo)       
# PROPOSED ADD COMPONENT
using "extended KiCAD component selection"

 ![](https://github.com/auphofBSF/KiCadDDM/blob/master/media/image2.png)  
# PROPOSED EDIT VALUE/FOOTPRINT/PARAMETERS 
using extended KiCAD component properties
![](https://github.com/auphofBSF/KiCadDDM/blob/master/media/KiCadEEschemaComponentPropertiesDDMextension.gif)

