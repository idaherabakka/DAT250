technical problems that you encountered during installation and use of Java Persistence Architecture (JPA) and how you resolved
- experiment 1:
  - I got some error when I tried to run the code, so I had to download intellij and run it there.
  - had to start over again several times because of errors and updates in the original project
  - had to download intellij to watch database, but couldnt run anything, so i had to download the pro with student licence to make it work
- experiment 2
  - "cascade was not persisted"-error, forgotten to persist more than person in Main.java
  - tostring error: could not use lombook with @data, but had to spesify with @getters, @setters and @NoArgsConstructor in Bank-class and Address-class
  - Test failed, expected some values but got empty. I had forgotten to actually add the data and connected it to the right entity
 

a link to your code for experiment 2:
- https://github.com/idaherabakka/dat250-jpa-example

an explanation of how you inspected the database tables and what tables were created. For the latter, you may provide screenshots.
- First, I needed to set up the database , after it was created. In Database on the right side in intellij, I clicked "+" to add a new ->data source -> apache derby and filled in name, user and password from persistence.xml and tested connection. If the connection succeded, I could apply the database.
- And then I could see the vizualization by righ click the root of the database -> Diagrams -> Show visualization
- Screenshots
<br>
![Database visualization](https://user-images.githubusercontent.com/97961839/190235742-723b0acd-d97e-473a-9cd2-80c416676b74.png)

any pending issues with this assignment that you did not manage to solve
- No, I did not have any issues that i did not manage to solve 
