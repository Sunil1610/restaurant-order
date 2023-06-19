# restaurant-order
Restaurant ordering service

Stack - Java, react, MongoDb

Design

Collections

Items Collection - 
  item id
  restaurant id
  Food item
  Description
  Type(Starter/Main Course etc.)
  Veg/Non veg, Alocholic/Non alcoholic

Image/Metadata collection - 
  item id to metadata

Order Collection - 
  order id
  List<item id, instructions>
  restaurant id
  quantity


APIs - 
  Get all items in restaurant - grouping in ui
  Add item to an order
  Remove item from an order - Admin api
  Lock order
  Unlock order - Admin api
  Generate bill
  
  
