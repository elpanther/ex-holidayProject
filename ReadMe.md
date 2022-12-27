### Happy Holidays Devs

Welcome to the Code Differently holiday project. In this project you will be recreating the classic song but with 
a Code Differently twist. Instead of the “12 Days of Christmas” you will be coding the “12 Days of DevShop!”. 
Not only will you recreate the song, but you will also perform calculations to determine the daily and 
total cost of all items.

Before you begin, there are a few acceptance criteria that must be met.
1. You may not alter any of the values provided by CD
2. Your code is not valid if the character spacing and punctuation are not correct.
3. You may work as a team, but each member must push their own version to GitHub Classroom.
4. You may make additional classes.

### Phase 1

###Step 1

Iterate through the **holidayList[]** array to print each item in the array with their corresponding number. Keep in mind that arrays begin with a 0 index.

Example:

1 A Hoodie from Code Differently  
2 Scrapple Sandwiches
3 VR Headsets  
4 virtual backgrounds
etc...

###Step 2

Iterate through the **holidayList[]** array in reverse with their corresponding number

Example:

12 Beat-boxers-Beat-boxing  
11 Trap-Rappers-Rapping
10 Djs-dj'ing
9 Tik-Tok Dances
etc...

###Step 3

Iterate through the **holidayListPrice[]** array and print each price in the array on a separate line. 
Each item must be in proper currency format with 2 decimal places.

Example:

$280.18
$300.00
$106.25
$149.99
etc...

###Step 4

Iterate through both list and print the item name and the price on the same line. The item and price must be separated by a “,”.

Example:

A Hoodie from Code Differently, $280.18
Scrapple Sandwiches, $300.00
VR Headsets, $106.25
Virtual Backgrounds, $149.99
etc...

###Phase 2

###Step 1

Create 3 variables of type String to hold the repetitive starting line of each verse.

messageBegin, suffix, messageEnd

messageBegin = “On the “
suffix = correct suffix for a given number

Ex:

1= “st”
2 = “nd”
3 = “rd”
4 = “th”
etc...

messageEnd = “ day of DevShop my team mate gave to me: “

###Step 2

Iterate through **holidayList[]** array, combine your string variables to recreate the song.

Example:

On the 4th day of DevShop my team mate gave to me: 4 virtual backgrounds,
3 VR Headsets, 2 Scrapple Sandwiches and A Hoodie from Code Differently.

On the 5th day of DevShop my team mate gave to me: 5 AIR FORCE ONES!
4 virtual backgrounds, 3 VR Headsets, 2 Scrapple Sandwiches and A Hoodie from Code Differently.

On the 6th day of DevShop my team mate gave to me: 6 Gamers Gaming,
5 AIR FORCE ONES!
4 virtual backgrounds, 3 VR Headsets, 2 Scrapple Sandwiches and A Hoodie from Code Differently.


Things to keep in mind:
1. Each new verse must have the correct day number and suffix
2. Each item must have its proper number
3. The 5th item must be capitalized and have an “!” each time it appears
4. The 5th item must be on a separate line (except for day 5)
5. There must be a line break between each new verse

###Phase 3

###Step 1

Create 3 variables of type double to be used for money calculations:

itemCost, dailyCost, grandTotal

###Step 2

Add the itemCost for each new item, to the end of each verse. Note: The items in the **holidayListPrice[]** is for 1 item. 
You must calculate the cost for each item based on the corresponding day.

Example:

virtual backgrounds = $149.99 each

On the 4th day of DevShop my team mate gave to me: 4 virtual backgrounds,
3 VR Headsets, 2 Scrapple Sandwiches and A Hoodie from Code Differently.
virtual backgrounds cost: $599.96

###Step 3

Add the dailyCost of all items given on the current day, to the end of each verse

Example:

On the 4th day of DevShop my team mate gave to me: 4 virtual backgrounds,
3 VR Headsets, 2 Scrapple Sandwiches and A Hoodie from Code Differently.
virtual backgrounds cost: $599.96
Daily cost of all items: $1,798.89


Step 4

Add the grandTotal of all items given each day after all 12 days of giving have been completed.

Example:

Grand Total: $197,148.36 

Good luck Devs. Looking forward to seeing your solutions.

 

 

 
 