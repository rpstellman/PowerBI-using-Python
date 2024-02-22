<h1>PowerBI Using Python</h1>

<h2>Description</h2>
Project consists of pulling financial data from the web (Yahoo Finance via Python yfinance) in PowerBI using Python.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python: pandas / yfinance</b> 
- <b>Matplotlib</b>
- <b>Seaborn</b>

<h2>Environments Used </h2>

- <b>MacOS</b>
- <b>Microsoft PowerBI via Virtual Machine</b>

<h2>Program walk-through:</h2>

<p align="center">
Raw Yelp Business Data in JSON: <br/>
<img src="https://i.imgur.com/LwyY6WM.png" height="80%" width="80%" alt="Raw Yelp Business Data"/>
<br />
<br />
Select data items and create SQLite table / file:  <br/>
<img src="https://i.imgur.com/jVbUHJx.png" height="80%" width="80%" alt="SQLite table creation"/>
<br />
<br />
Selecting Data File: <br/>
<img src="https://i.imgur.com/wtjzMb3.png" height="80%" width="80%" alt="Selecting Data File"/>
<br />
<br />
Parsing the JSON data:  <br/>
<img src="https://i.imgur.com/YysCMec.png" height="80%" width="80%" alt="Parsing the JSON data"/>
<br />
<br />
Only Pulling 100 Businesses at a time:  <br/>
<img src="https://i.imgur.com/cespm0q.png" height="80%" width="80%" alt="100 Business Limit"/>
<br />
<br />
Dumping Data into Database:  <br/>
<img src="https://i.imgur.com/E1zcbbw.png" height="80%" width="80%" alt="Data Dump"/>
<br />
<br />
Observe the database:  <br/>
<img src="https://i.imgur.com/ZC7hhYl.png" height="80%" width="80%" alt="Business Database"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
