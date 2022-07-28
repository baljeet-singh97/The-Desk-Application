# The-Desk-Application
Introduction:
This is an The-Desk-Application App. In this app user can add,
delete, sort, search the expenditure. Fixed some bugs in search
method and in sort method.

Installation Guide:
1. GitHub link: https://github.com/baljeet-singh97/The-Desk-Application
2. Download the entire project as Zip in local system.
3. import the project in Eclipse IDE

How to use:
1. After running the code you will see the window like:
2. Select an option (for eg: 1). Then program will print all the

expenditure data on the screen as shown in below image

Bug Fixed:-→
1. Search Expences
Used scanner class to take input from the user.
Taking input in variable ‘key’ from the user as we need to search the key in the data
Int key = sc.nextInt();

ArrayList contains() method in Java is used for checking if the specified element exists in
the given list or not.
It returns true if the specified element is found in the list else it returns false.

If(arrayList.contains(key))
 System.out.println(“yes it contains “ + key);

2. Sort Expences:->
java.util.Collections.sort() method is present in java.util.Collections class. It is used to sort
the elements present in the specified list of Collection in ascending order.

It works similar to java.util.Arrays.sort() method but it is better then as it can sort the
elements of Array as well as linked list, queue and many more present in it.

Collections.sort(arrayList);
 System.out.println(arrayList);
