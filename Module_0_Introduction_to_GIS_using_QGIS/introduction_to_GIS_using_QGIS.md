# MODULE 0 - INTRODUCTION TO SPATIAL DATA AND GIS USING QGIS

## 1. SPATIAL DATA

- ***What is data:*** Ordered collection of information arranged in rows (records) and columns ( attributes/fields).The rows represent unique records and the columns the attributes related to the records.

| Record id      | attribute 1 | attribute 2 | .....  | attribute n |
| ----------- | ----------- | ----------- | ----------- |------------|
| item 1      | value       | value       | value       | value       |
| item 2   | value        | value       | value       | value       |
 | ....   | .....        | ....       | ...       | ...       |
| item n   | value        | value       | value       | value       |


> #### EXERCISE 1 - Create a table
> 
>  - Create a table to collect information of the main islands in BVI
>
>   | town    |  
> | ----------- |  
> | Tortola  |  
> | Beef Island  | 
> | Anegada  |
>
>  - What attributes you would include? Add the attributes to your towns table ( population, employe , etc. ) 
>
>   | town    |  population | area (square miles) |
> | ----------- | ----------- |   ----------- | 
> | Tortola  |  23,491 | 21.5 |
> | Virgin Gorda | 3,930 |8  |
> | Anegada  | 285 |  15 |
> 
>  - Scale the table to include other geographical features of BVI  ( islands, cay, bays , beach , etc.  ). How you would indicate the category of the feature you are including in the table? Add another two geographicl features to this table
>  
>   | feature    | category | population | area (square miles) |
> | ----------- | ----------- |   ----------- |  ----------- | 
> | Tortola  | island | 23,491 | 21.5 |
> | Virgin Gorda | island | 3,930 |8  |
> | Anegada  | island| 285 |  15 |

- ***What is SPATIAL data:*** Any information collected in the world is related to a spatial location.  Abstraction of the real grographical features into spatial vector objects.



> ***EXERCISE 2***
>
> - A town can be represented as a point or polygon . How you would represent houses, a river, a road or a lake ? 
> - What is the type of spatial object you would use to represent the  spatial information related to  Exercise 1 ?
> - How you represent the spatial location of the records in Exercise 1 table (POINT, LINES or POLYGONS)?
> - Add two new columns to your tables to include the geographical information of latitude and longitude
> - Use teh [BVI map](http://www.skyviews.com/british-virgin-islands-map/BVI_Islands_Mapside.jpg) and [google maps](https://www.google.com/maps/@18.3995843,-64.694019,1589m/data=!3m1!1e3!5m1!1e4) and get the coordinates in 
