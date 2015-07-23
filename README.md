Extra credit problems for the MVC section of the .NET bootcamp

## Exercise 1: MVCMovie App

Let's add additional functionality to the MVC Movie app you did as your first MVC tutorial.

NOTE: Create and use a github branch as you implement these features. If you work off your master branch and don't get everything completely working then you will break your code and the app won't work.

* Add a rating field linked to an enum to your model. Implement the ratings field(G, PG, PG-13, R) in your create/edit views as a dropdown. You'll need to change your code in the MovieController, the model, and every view where the rating can be set or displayed.
* Modify the Movie view index file to display the database information in a "prettier" format. Use your imagination. Anything is acceptable as long as you think it looks better than the simple rows the tutorial creates. You should still be able to access all the CRUD functions the current design allows in your new design.

Bonus: Add another field with enum for the movie genres.

## Exercise 2: Address Book x2

* Redo the address book you did as a console app as a MVC application. You will need to start a new project, but depending on how you wrote the original code, you might be able to reuse some of your work.
* Try to do this project without looking at the insturctions for the Movie app. This project can essentially be done by mimicking the Movie app project. Because no new skills outside of what was already taught are needed, you'll learn more by doing as much as possible from memory.
* Implement your search function using LINQ syntax.
* Add appropriate validation and/or attributes to your model


## Exercise 3: Dealership

Create a MVC project for an auto dealership. You will need at least two models. Inheritance may or may not be needed.

* A car model should track: Make, model, year, MPG, color, and MSRP. You may decide other properties are also needed. For simplicity you may treat all types of vehicles the same(i.e. trucks and cars could use the same model).
* A customer model which tracks the car purchased by linking to the car model.
* Use individual user accounts. The accounts have two levels of access. Admin with full CRUD and customers, who can only browse available cars.

Your app should be able to do the following:

* Be able to search by make, model, color, or price range.
* Include a picture of the vehicle. There are several ways to do this.
* Link the specific vehicle object to a specific customer when a sale is recorded.
* Use the about page to display aggregate details of the dealership inventory. This page should be able to sum the total number of each car of specific year, make, and models.
    
### Add at least one of the following features

* Create a feedback system for each type of car (Year, Make, Model). The feedback should be linked to customer accounts.
aggregate* On the car detail page add the ability for customers browsing the site to input the expected #miles they will drive per year. This should link to a graph that displays the annual expected cost to operate the car. The graph should have categories for fuel, insurance, maintence, etc...
* Add a compare car feature where a customer can select two cars to display side-by-side.

The dealership app will take some stretching of your skills. You might not be able to do it until we've covered some additional lessons in class. That's OK.


## Exercise 4: Museum
Create a MVC project for an art museum. 

* All art is contained in galleries.
* Your art model should contain at least: a text description, a type(painting, pottery, sclpture, doo-dads, etc), and the gallery it is displayed in.
* A gallery should be created for each style of art displayed(i.e. Egyptian, Asian, Early Man, American, etc..)
* Create an artist class and add an artist field to the art model. Be able to display all art from that artist.

The curator of the museum should be able to:

* Add/remove art
* See all the art in the museum
* List all art in specific galleries
* Include photos of your art pieces

Bonus: 

* Add user accounts so that only the curator can preform CRUD functions, and all other users can only view the items in the museum.