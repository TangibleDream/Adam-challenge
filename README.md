<b>Adam's challenge</b> is to build an API out of clojure that will perform 3 different sorts of text files with varied delimiters for 5 fields.<br/> 
The fields are 

 - LastName
 - FirstName
 - Gender
 - FavoriteColor
 - DateOfBirth.

 The delimiters are 
 

 - comma
 - pipe
 - space 

The file is sorted by

 - gender (female, male) then last name ascending
 - birth date ascending
 - last name, descending

API

 - A post command can temporarily add a new data row into the sort (Post/records)
 - GET/records/gender 
 - GET/records/birthdate 
 - GET/records/name
