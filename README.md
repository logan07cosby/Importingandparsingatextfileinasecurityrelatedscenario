<h1> Importing and parsing a text file in a security related scenario</h1>


<h2>Description</h2>
In this Project, experience using Python to develop algorithms that involve opening files and parsing their contents will be demonstrated. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Coursera</b>
- <b>Python</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Algorithm walk-through:</h2>

<p align="center">
Assigned file name as a string to the import_file variable: <br/>
<img src="pyth 1.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
Used a with statement to open the file:  <br/>
<img src="pyth 2.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
Used the .read() method to convert it into the string: <br/>
<img src="pyth 3.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
Used the .split() method to convert the ip_addresses string into a list: <br/>
<img src="pyth 4.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
Used For loop to remove any IP addresses from the allow list that is contained in the remove_list: <br/>
<img src="pyth 5.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
used the .join() method to update the allow list: <br/>
<img src="pyth 6.PNG" height="80%" width="80%" alt=""/>
<br />
<br />
 used another with statement and the .write() method to update the file: <br/>
<img src="pyth 7.PNG" height="80%" width="80%" alt=""/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
