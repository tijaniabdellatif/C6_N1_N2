##database :

## database.php and index.php :
create a database with a table called :

shoutit(id , user , message , time)

inserting some data 

output the data inserted in the UI

in the file database.php

use mysqli_connect to connect to your database , make checkes to be sure that's is connected 

include the right files 

Creating the first query and print result into the UI

replace the static content with the dynamic content

## validate and insert Datas : 


in the form fields we gonna take data from those inputs validate it to be stored in the database and also 

printed in the front end 

## process.php

first : check if the form is subbmited use the security methods to secure inserting harm words injected by the users and gather what's inserted

second : dont forget the time, configure your file with the correct function which make you using the right time zone and format the date into (h : i : s);

check if the user is not setting the values in the form or is letting them empty


if the user file the fields 
 
 insert data into database check if the query is inserted

 if is inserted redirected to index.php

 if it's not redirected to index.php with the error message in the URL USE the method get to display the error in the UI ( $error = "Please fill the name and the message")
