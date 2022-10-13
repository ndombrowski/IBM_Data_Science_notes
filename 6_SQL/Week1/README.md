#downloaded csv from

#converted to sql database
csvs-to-sqlite Film_Locations_in_San_Francisco.csv Film_Locations_in_San_Francisco.db

#read with datasette
datasette Film_Locations_in_San_Francisco.db
