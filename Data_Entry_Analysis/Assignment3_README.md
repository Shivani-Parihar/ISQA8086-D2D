### Assignment 3 - Data Entry Analysis

#### Problems with the provided datasets are -

  1. The datasets have missing values, like we have values missing for the Temp field in zoo-temp-main dataset and colony diameter, density and Temp field values missing for pond2010 dataset

  2. Some of the column or field name does not give any information about what kind of data is being stored for the dataset
    * For example the column/field in pond2010 dataset, 'z' does not provide any description or information. I believe if the dataset makes use of any sort of acronym there has to be a Note or a legend included to let user know what field it represents or what data is being stored

  3. In the given dataset some of fields do not have an unit associated to it which might be end up being a problem to the user

  4. As we know the data is recorded at various times from day to night but our dataset shows multiple entries for the same date but do not tell us at what time of the day the data was recorded

  5. There are some entries/records in the dataset which are highlighted and the dataset does not explain why it has been highlighted using a different color which might create confusion to the user. Even if the data is highlighted, it would be a good idea to add legends at the bottom or in a different sheet to let user know why the data is highlighted

  6. In zoo-temp data file it has calculated the average for cuni and chippo colony size which is not relevant to user as the user can calculate the average and can perform other mathematical operation as per the user's need

  7. The plotted graph does not have a label for the x & y axis. Without any label it is very hard to tell what data is being plotted

#### Suggestions to improve the dataset -

| Date  | Year |  Time_of_Recording |  Species |  Depth (mts) |  Temperature (F or C) | Species #/L | Density (kg/m3) | Species colony size | CHLA |
|---|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |   |   |   |   |

* The above table is my suggestion on how the data should have been arranged
* Density is not known for all the years so it depends on the user if it should be included in the dataset. Generally if we have missing data in that case one way is to remove the field or to put a negative value for the missing record
