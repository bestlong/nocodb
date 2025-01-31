---
title: 'Views'
description: 'Understanding Views in NocoDB!'
position: 600
category: 'Product'
menuTitle: 'Views'
---

## What's a View?

In a table, you can use different views to display your data. You can show specific fields in a View. You can also apply Sorting or Filtering to the View. Each View is independent, which means the configuration applying to View 1 will not apply to View 2. 

To navigate different views, we can select the target one in the view sidebar. By default, Grid View will be created for you after creating the table. You can create multiple views of a type, as long as they have unique View names.

## View Menu Bar

To work with `Views`, use View menu-bar on the right hand side - 
- <1> Toggle View menu-bar.
- <2> Displays created view-list for the selected table
  - Currently active view is high-lighted   
- <3> Add new view to the list

![image](https://user-images.githubusercontent.com/35857179/194814369-53fa8875-7610-4849-9a91-f94096b15b3f.png)

## View Types

### Grid View

Grid View, as a default type of view, allows you to display your data in a spreadsheet-like interface.
  
![1010-2 Grid](https://user-images.githubusercontent.com/35857179/194824161-ce5c4875-4425-40b7-b932-8176271e4f1e.png)

### Form View

Form View allows you to arrange fields in a form to input data.
  
![1010-2 Form](https://user-images.githubusercontent.com/35857179/194824127-b400f9c8-18a7-4a37-b8c3-7d279e9976af.png)

You can drag-drop columns from the form to form-field-menu-bar as requried.

### Gallery View

Gallery View allows you to display images as thumbnails with other fields just like a gallery.
  
![1010-2 Gallery](https://user-images.githubusercontent.com/35857179/194824141-04c76a4e-2cae-448f-a842-c79f5bce339d.png)
  
### Kanban View

Kanban View allows you to visualise your data using cards at various stacks.

![1010-2 Kanban](https://user-images.githubusercontent.com/35857179/194824164-97ca897a-3af4-42ab-8812-534afaf23396.png)
  
## View Permission Types

We can apply permission to each View. By default, Collaborative Views will be used. To see or change the view type, expand `view-tool-bar-menu` as shown below. 

![Screenshot 2022-09-09 at 3 46 33 PM](https://user-images.githubusercontent.com/86527202/189328303-edbf35b5-f793-4e06-9dbf-89d045a38482.png)
<!-- ![Screenshot 2022-09-09 at 3 19 00 PM](https://user-images.githubusercontent.com/86527202/189323062-5be6bd3f-366a-4be2-8de0-df30fcd1808e.png) -->
<!-- ![image](https://user-images.githubusercontent.com/35857179/163343598-fd81edea-f160-41ee-8bb2-3ef1eee5348d.png) -->

### Collaborative Views (default)
- Collaborators with edit permissions or higher can change the view configurations
<!-- ![image](https://user-images.githubusercontent.com/35857179/163343959-7e2f43cb-1a1f-4f36-985c-ca91db262f98.png) -->

### Locked Views
- No one can edit view configurations until it is Unlocked
- All collaborators can only READ data from such views

### Personal Views
- Only you can edit the view configuration. 
- Your personal views are hidden for other collaborators
- Are not available currently; will be enabled in future release
<!-- ![image](https://user-images.githubusercontent.com/35857179/163343845-b07f9d3f-5a83-4dfd-8d45-9cc59b3512c3.png) -->


## View Operations
  
![Screenshot 2022-09-09 at 3 27 46 PM](https://user-images.githubusercontent.com/86527202/189325592-302054da-a755-4a92-a322-80aed184ca3b.png)


### Create a View

Click '+' in View-menu sidebar, as shown in <3>.

### Rename a View

Double click on `view-name`, edit, <enter>.

<!-- ![image](https://user-images.githubusercontent.com/35857179/163353802-1da52cec-ae17-4ced-8679-62d7180683ec.png) -->

### Delete a View

Hover the target View and click the delete icon, as shown in <2>.

<alert>
You cannot delete the very first Grid View (termed as `Default view`).
</alert>

<!-- ![image](https://user-images.githubusercontent.com/35857179/163359795-f4420402-b2a6-41d8-b48c-f0dea8b9abbe.png) -->

### Duplicate a View

Hover the target View and click the copy icon, as shown in <2>.

<!-- ![image](https://user-images.githubusercontent.com/35857179/163353865-7275499e-c685-44f4-906c-ba08f0ee419e.png) -->

### Reorder a View

Hover the target View and re-order it as needed by drag-drop the drag icon, as shown in <1>.

<!-- ![image](https://user-images.githubusercontent.com/35857179/163359674-c4aeff74-1cb4-498d-b79c-c6ddf84ad352.png) -->
