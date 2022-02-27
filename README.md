# Pandas

Loading_Data:
   - Load CSV data
   - Load Table data
   - Load Excel Data
   - Load SQL data
   - Load JSON data
   - Load XML and HTML data
   - Load Clipboard data
   - Load dataframe
   - Load data from Github
   - Load Binary data Formats
   - Load HDF5 data Formats
   - Web APIs data
   - Set the working directory
   - with open data
   - zip folder
   - Create date time
   - Load data from SQL lite, sql, mongodb
   - pandas cheet

Exporting_Data:
   - CSV data 
   - Excel data
   - Json data
   - HTML data

Creating_Objects
   - DataFrame 
   - Series 
   - Add Date Index
   
Viewing/Inspecting_Data
   - head/tail/info/describe/apply()
   - shape

Data_selection
   - df[col]/df[[col]]
   - iloc[0]/loc[0]

Data_Cleaning
   - df.columns=['a','b']
   - df.isnull()
   - df.notnull()
   - df.dropna()
   - df.dropna(axis=1)
   - df.dropna(axis=1,thresh=n)
   - df.fillna(x)
   - s.fillna(s.mean())
   - s.astype(float)
   - s.replace()
   - df.rename(columns=lambda x:x+1)
   - df.rename(columns={'old_name':'new_name'})
   - df.set_index('column_one')
   - df.rename(index=lambda x:x+1)

Filter, Sort, and Groupby
   - df[col]>0.5
   - df.sort_values(col1)
   - df.groupby()
   - df.pivot_table()
   - df.apply(np.mean)
