# ExpITExtraCredit2-MVC
Extra credit problems for the MVC section of the .NET bootcamp

## Exercise 1: MVCMovie App

Let's add additional functionality to the MVC Movie app you did as your first MVC tutorial.

* Change the rating input from a text input where the user can input anything they want to a dropdown. Link the dropdown to a enum you define in the Movie class file. You'll need to change your code in every view where the rating can be set or displayed.
* Modify the Movie view index file to display the database information in a "prettier" format. Use your imagination. Anything is acceptable as long as you think it looks better than the simple rows the tutorial creates. You should still be able to access all the CRUD functions the current design allows in your new design.

## Exercise 2: Address Book x2

* Redo the address book you did as a console app as a MVC application. You will need to start a new project, but depending on how you wrote the original code, you might be able to reuse some of your work.
* This project can essentially be done by mimicking the Movie app project. No new skills outside of what was already taught.
* Implement your search function using LINQ syntax

## Exercise 3: Dealership

Create a MVC project for a auto dealership. This dealership sells cars, fuel efficient cars, and trucks. The dealership also has a policy where a customer can place a 5% deposit down on a vechile and then take it home for 24hrs for test driving.
Your app should be able to do the following:

* Create models for the three types of vehichles sold. Use inheritance where appropriate.
* Track customers who bought vehicles and people who have vehicles out on test drives and when the vehicle is due back.
* The dealership manager should be able to see quickly how many of each type of vehicle are on the lot vs out on test drives.

Bonus: On the various car detail pages include a picture of the vehicle. There are several ways to do this.