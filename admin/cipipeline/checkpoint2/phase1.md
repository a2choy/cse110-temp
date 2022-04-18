## by phase1 (checkpoint1):
Alexandre Marques was assigned the task of testing our progra, given that he can ask for help anytime and have more team members working with him.   
We all practiced writing tests and unit tests in the lab at that point, and Aleaxndre used what he learned from lab to write simple, almost dummy, tests in our project's repo. Just to set up the testing environment and have some tests running automatically. Note that at this point, our journal wasn't functional enough to have unit tests. We just had a walking skeleton which is solely static and front-end. The most simple of out tests was something like:  `expect(1).toBe(1)`.  
Note: Alex didn't need help completing this, and the other team members were working on making the journal more functional for unit tests.
## by phase2 (checkpoint2):
For phase 2 of the CI/CD pipeline, we added unit testing to our testing scheme in order to check the basic functionality of our website.  
Primarily, we test the functionality of ‘pagescript.js’, which is in charge of saving data to the database, loading data from the database, as well as other main functionalities of our website.  
We have unit testing of the ‘createComp’ method, which checks whether the component is created successfully, and whether the name and height of the component is set correctly. We also use unit testing to test the functionality of ‘addobj’, which checks whether the object is created successfully, whether the name, height, classname, order, and counter of the objects are set correctly, whether the length of the objectlist is set correctly, and so on. We also test the functionality of ‘moveUp’, ‘moveDown’ and ‘removeComp’ methods respectively to ensure that our website is working as expected.  
Now we still haven’t added unit testing to all existing methods, but we plan to add those in the following days as we make changes or add new components to our website. In the end, when we finish most parts of our website, we would have unit testing checking the database, navigation bar, menu bar, calendar, as well as our TODO list. We would also have automated testing set up for our code by that time.