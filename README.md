# Laika Pawperites Manager
Project to handle properties on a hierarchical way been able to inhearited properties from a parent object unto children objects using a unique map of key structure as an example 

lets said that  you have a parent  object 

### Object Doggo:
---
´´´json 
{
  "id":"doggo",
  "parent_id":null,
  "legs":4,
  "fur":"short"
  "double_coated":true
}

´´´


and a Childrent Object:
### Object Laika
---
´´´json 

{
  "id":"laika",
  "parent_id":doggo,
  "legs":4,
  "fur":"short"
  "double_coated":true
}

´´´




