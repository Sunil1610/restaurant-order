# restaurant-order
## Restaurant ordering service

Stack - Java, react, MongoDb

## Design

## Collections

### Items Collection -  <br />
  item id <br />
  restaurant id <br />
  Food item <br />
  Description <br />
  Type(Starter/Main Course etc.) <br />
  Veg/Non veg, Alocholic/Non alcoholic <br />

### Image/Metadata collection -  <br />
  item id to metadata <br />

### Order Collection -  <br />
  order id <br />
  table id <br />
  List<item id, instructions> <br />
  restaurant id <br />
  quantity <br />


### APIs - 
  #### User Facing 
  Get all items in restaurant - grouping in ui <br />
  Add item to an order <br />
  Lock order <br />
  Generate bill <br />

  #### Business facing
  Remove item from an order - Admin api <br />
  Unlock order - Admin api <br />
  Add Table - Admin api <br/>
  
  
