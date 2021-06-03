### OOP-JAVA-Project
#### Library Managment System

Author: Mehmood Yar Baig

This is a project taken from github as semester project for the Object Oriented Porgramming in java. The previous project worked on a basis of image view used in scene building which was later changed by importing fontawesome libraries and using the icons instead of image viewers. Moreover, the original code was running in java JRE 8.1 and was giving issues in JRE 11, for which the while code was debugged. Moreover, the gui of the original project was more old fashioned which was changed to make it more attractive and easy to work with. 

This desktop app will assist the librarian to keep track of all the books in the library through a database. Moreover, it will help to search for the books by name as well as ID of the book. Furthermore, the app can help in keeping track of time of issuing and returning of the books. The important part is the members option, it can store the data of regulars memebers whether they be students, faculty or other staff and can keep record of all memebers and their issuances. This app can further be developed to connect with the internet to send an email to the member if the dealine is coming ahead so the book can be returned. Also, a login service can be added such that the system can be more secure. 

Libraries:
Download the JavaFX SDK: https://gluonhq.com/products/javafx/

fontawesome: https://bitbucket.org/Jerady/fontawesomefx/downloads/

jfoenix: https://github.com/sshahine/JFoenix

These libraries are also included in the lib folder. 

Virtual Machine Settings:
Add JavaFX library: File -> Project Structure -> Libraries -> add library path->C:\javafx-sdk-11.0.2\lib

Add VM Options: Run-> Edit Configuration -> modify options -> add vm options --module-path %PATH_TO_JAVAFX_SDK/LIB% --add-modules javafx.controls,javafx.fxml
