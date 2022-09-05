# People - Telosys 4 model 

This model aims to show how to use "many to one" relationships with different types of Foreign Keys (explicit or not).

It gives examples of using link annotations : 
- @LinkByFK(xx)
- @LinkByAttr(xx)
- no annotation = FK inference

## Entities 
- **Area**
- **Country**
- **Department** (composite PK)
- **Person** 
- **Town** 

## Relationships
- Person 
     - 1 Country
     - 1 Department (composite FK)
     - 1 Town 
- Area 
     - 1 Country 
- Town 
     - 1 Country 
    