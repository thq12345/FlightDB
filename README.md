**Readme:**

First of all, if you are using MacBook, please follow the following link to finish the MySQL installation:

[https://cs3200.weebly.com/uploads/8/5/4/6/85462436/mysql\_installation\_mac8.0.x.pdf](https://cs3200.weebly.com/uploads/8/5/4/6/85462436/mysql_installation_mac8.0.x.pdf)

Or you are using windows, please follow this link to finish MySQL installation:

[https://cs3200.weebly.com/uploads/8/5/4/6/85462436/mysqlinstaller2018.pdf](https://cs3200.weebly.com/uploads/8/5/4/6/85462436/mysqlinstaller2018.pdf)

Please download the installer.

And in the installer, please click add button:

![](RackMultipart20210117-4-xkf4im_html_cc008e7880403ef3.png)

And then, install everyone which you have not installed in the list, and continue click next to finish the installation.

Secondly, you need to install java 11 and Eclipse.

For java 11: [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

![](RackMultipart20210117-4-xkf4im_html_be5f1ae2a2515e8e.png)

Download JDK and please make sure choose the JDK option in the installation.

For eclipse: [https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/)

Download it and install it. Remember select Eclipse IDE for java developer when installing.

And then you should open your MySQL server and enter local MySQL connection. Then open the &quot;file&quot; menu and open MySQL script, choose the MySQL file we submitted and execute all of the file.

The next step is open Eclipse.

There are two options:

1. If you want to just import single java file, you should open the Eclipse and then choose &quot;File&quot; menu, choose new and then project. Choose java project and click next, give this project a name you want, then click next and cancel &quot;create module-info.java file&quot; and click finish. Then right click this project and choose &quot;build path&quot; and then &quot;Add External Archives&quot;, find the location you install Connetor/J (for me, it is on C:\Program Files (x86)\MySQL\Connector J 8.0). And then left click this project and choose the &quot;scr&quot; and right click &quot;scr&quot;. Then you need to right click &quot;scr&quot; and choose new and create a new Package and name it as javamysql. And then choose this package and right click it and choose import, choose &quot;File System&quot; and click next, browse the location where you store our java file (it is in the folder single java file, its name is Flight database front End.java), and then there will be a window like this:

![](RackMultipart20210117-4-xkf4im_html_c5c4314ce7652f06.png)

You should select our java file on the right part and click finish. Finally, you can just click run and follow the hint to use this project.

1. Or you can import the whole java project.

![](RackMultipart20210117-4-xkf4im_html_1f71c9d09d7125f6.png)

Right click on the blank area of Package Explore, choose import:

![](RackMultipart20210117-4-xkf4im_html_d7f727bf6d01dab9.png)

And then choose &quot;Existing Projects into Workspace, click next.

Then select root directory. It is where you store our java project (You should open the zip file and find two folders, one of them is named as java project. Open it and select &quot;Project of Tianhao and Ruizhe&quot; in the &quot;Select root directory&quot;. Then select project &quot;Project of Tianhao and Ruizhe&quot; and click finish. Finally, you should check if this project has included archive &quot;mysql-connector-java.jar&quot;. If not, you should import it for the project. And how to import this archive has been explained in the first option.

**Command List:**

When you enter the project and make it run, you should follow the hint. AT first, you should enter your MySQL server username and then password.

Then you need to choose one from three command: modify (allows you to edit the database), search (allows you to search data from database) and exit (to leave program).

If you choose &quot;modify&quot;, you should choose one from three command: add (insert data into database), delete (delete data from database) and change (update data from database).

And then you should choose a table from airline, airport, country, plane, planecompany, route to edit.

And then you will need to follow the hint, according to the your choice on add/delete/change to give your limitation on the data you want to modify, like choose a column and insert data for it, or choose a column and give a limitation to find all data fit your requirement and edit them.

If you choose search, you will choose from procedure/table.

If you choose procedure, you need to choose a procedure name from a list the program give you, and then give the procedure an appropriate input.

If you choose table, you need to choose a table to see the data in this table.

If you choose exit, the program will end.

And after you search/modify successfully, you need to choose from Y/N, Y means you will continue the function you are using, and N will make the program return to the main menu to choose modify/search/exit.

All above is how to use this project.
