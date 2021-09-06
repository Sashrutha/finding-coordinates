A security Company sends and receives the location coordinates in an encrypted manner. The encrypted coordinates will be in form of two strings, one will be the latitude and other longitudes

Decryption rules as follows:

The last character of encrypted string denotes the direction latitude string(only two [n-North, s-South])  longitude string(other two [e-East, w-West])
Except last character the string denotes integer value irrespective of  whether it is a latitude string or longitude string  
The Integer part of the coordinate can be decoded as (Count of letter with maximum occurrences – Count of letter with minimum occurrences in string)
All letters are in lower case
Time Limit: 1sec

Constraints : 4 <length of string <= 1000

Sample Test case : 

Input:  
babbeddcs
aeeaecacw
Output:  
2 South 1 West
[finding_coordinates.txt](https://github.com/Sashrutha/finding-coordinates/files/7117534/finding_coordinates.txt)

# finding-coordinates
