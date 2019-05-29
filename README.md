Adam's challenge is to build an API out of clojure that will perform 3 different sorts of text files with varied delimiters for 5 fields.
The fields are LastName, FirstName, Gender, FavoriteColor, and Date of Birth.
The delimiters are comma, pipe, and space.
The sorts are by gender (female, male), then last name ascending,  birth date ascending, and last name, descending

A post command can temprarily add a new data row into the sort  (Post/records)
GET/records/gender
GET/records/birthdate
GET/records/name
