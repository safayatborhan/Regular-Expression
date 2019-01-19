# Regular-Expression
https://www.youtube.com/watch?v=sa-TUpSx1JA

Text : 
CoreyMSchafer@gmail.com
corey.schafer@university.edu
corey-321-schafer@my-work.net


Comments : 

***[a-z0-9.-]+@[a-z-]+\.(com|edu|net)
this plus sign is used for if we have a bunch of characters and
after that we have something another or it can be the same
characters. let's see an example 

oreyMSchaferid
corey.schaferID
corey-321-schafer

here in these 3 lines, in first two there are "id" at the 
bottom of the strings. if we want to search whose have "id"
at the bottom of the string, we would be written like this : 
"[a-z0-9.-]+id"


Text : 
https://www.google.com
http://coreyms.com
https://youtube.com
https://www.nasa.gov


comments : 
"https?://(www\.)?([a-z]+)(\.+[a-z]+)"
we have searched all of it, but if you see closely we could 
have written like this : 

https?://(www\.)?[a-z]+\.+[a-z]+

the first "[a-z]+" are the url name and the second "[a-z]+"
are the domain name. we have made group each of them so that
we could make use of it later. and we can achieve the group 
content by writting "$1, $2 ..." like this. $1 is first group
$2 is second group. so on so forth....


** copy and replace C# property : 
(public\s\w+\s\w+)(\s\W\s(\w|\W)+)

$1 { get; set; } \n
