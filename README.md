# Codebasics-Excel-8-

## steps involved to complete this practice exercise

To complete this assignment, please follow the steps below:

1. Open a new Excel file and load the two provided CSV files using the "From Text/CSV" option. Then, open Power Query.

2. Change the data type of the "property_id" column to "text".

3. Some values in the "property_name" column are shown as "Atliq bay" instead of "Atliq Bay". Replace these values to show "Atliq Bay" instead.

4. Format the "property_type" column by removing any unnecessary leading or trailing spaces using the TRIM() function.

5. The "city|city_code" column includes both the city and city_code separated by a '|' symbol. Split this column to 

   separate these two entities and rename the resulting columns accordingly.

6. Create a new conditional column called "Availability Status". If "successful_bookings" equals "capacity", set the value to "sold out"; otherwise, set it to "vacant".

7. Create a new custom column called "occ%", which represents the ratio of successful_bookings to capacity. Change the data type to a percentage format. 
    ## [successful_booking]/[capacity]
   
8. Merge the two tables, "bookings_data" and "rooms_data", on the "room_id" column to add the "room_class" column to the "bookings_data" table.

   Reorder the columns so that "room_class" is next to "room_id".

9. Extract the month_name from the "date" column. You may use external resources or search engines such as Google to help you achieve this.

