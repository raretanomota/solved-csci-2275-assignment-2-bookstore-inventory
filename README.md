Download Link: https://assignmentchef.com/product/solved-csci-2275-assignment-2-bookstore-inventory
<br>
You are an entrepreneur and you plan to open a new bookstore with different types of item in your inventory. You will have books, CDs and magazines. Every item will have a serial number, name, published date (date, month, year) and price. But as you have 3 types of products they will have different properties. Books will have an ISBN number, number of pages, genre of book. CDs will have play time and description. Magazines will have its frequency of publishing and weather it is a local or international magazine.




Your task as the manager of the bookstore is to manage your inventory. You will read the inventory from a .txt file and store it in arrays for 3 different types of objects. You will then write search functionality. Given a serial number you have to print out all the details of the given number if it exists or else return false. Also write a function to add and remove stuff from the inventory.




Your code should have a class for each type of product. You should then store the inventory in 3 different arrays. Then you will write 3 functions:

<ol>

 <li>Insert – Given an item put it in the correct array</li>

 <li>Delete – Given a serial number it should delete the object from the array and shift the array if necessary.</li>

 <li>Search – Given a serial number print the details of the product (use function overloading) or print “Not found” if it is not found</li>

</ol>




Your main function will first read the initial inventory from a file and store it. Then, your program needs to read a file of actions that your program needs to perform. Both the files will be passed as command line arguments.




Contents of inventory file look like this:

1, Book, Harry Potter, 10-10-1995, 30, ISBN123456, 800, Fiction

Where 1 is the serial number, then we have what type of product it is, then name, publishing date, price. After that the columns will depend on what type of product it is.



















Contents of action file will be something like:




1

31, Book, Lord of the Rings, 1-09-1992, 20, ISBN131356, 2000, Fiction

2

1

3

21




To process the action file, group the lines in sets of 2. The 1st line of each set will tell you the action (1- Insert, 2- Delete, 3 – Search) The 2nd line will give you the new data for option 1 or will give you serial number that you have to search/ delete for option 2/ 3.




Also you should print your entire inventory at the end of the program




<h2>Before you start coding</h2>

Write the pseudocode for your program. There are a lot of details needed in this program that are not explicitly outlined in this write-up. If you just start coding before thinking through the problem, you might spend a lot of time re-doing your work.


