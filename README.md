Download Link: https://assignmentchef.com/product/solved-java-bir-project-2
<br>
Objectives:

<ol>

 <li>Create Classes and Objects.</li>

 <li>Process Array of objects.</li>

 <li>To use the String class to process immutable strings.</li>

</ol>

<strong>Palestinian Car Agency:</strong>

<strong>A car has many attributes. Consider underneath car has the following attributes</strong>

<table width="389">

 <tbody>

  <tr>

   <td width="186">Plate No</td>

   <td width="203">0123-A</td>

  </tr>

  <tr>

   <td width="186">Year manufacture</td>

   <td width="203">Current year</td>

  </tr>

  <tr>

   <td width="186">Month manufacture</td>

   <td width="203">Current moth</td>

  </tr>

  <tr>

   <td width="186">color</td>

   <td width="203">red</td>

  </tr>

  <tr>

   <td width="186">price</td>

   <td width="203">50,000.00</td>

  </tr>

  <tr>

   <td width="186">Manufacture by</td>

   <td width="203">Mercedes</td>

  </tr>

  <tr>

   <td width="186">Guarantee due to year</td>

   <td width="203">Current year</td>

  </tr>

  <tr>

   <td width="186">Guarantee due to month</td>

   <td width="203">Current moth+6</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Create a car class using at least the following 8 attributes: Plate No, Year manufacture,Month manufacture, color, and price. <strong><em>Note that both current year and moth are read from system</em></strong>.</li>

 <li>Create two constructors as follow:</li>

</ul>

No-argument constructor: that creates a car object using the default “Mercedes Benz” values in above example.

A constructor with arguments using the basic 8 attributes that mentioned before.

<ul>

 <li><strong>Your assignment should use the following two chart of UML:</strong></li>

</ul>

<table width="365">

 <tbody>

  <tr>

   <td width="365"><strong>Car</strong></td>

  </tr>

  <tr>

   <td width="365">-PlateNo:String<strong>–</strong>yearmanufacture:<strong>int</strong><strong>–</strong>monthmanufacture:<strong>int</strong>-color:String-price:<strong>double</strong>-manufactureby:String-guaranteedueyear:<strong>int</strong>-guaranteeduemonth:<strong>int</strong></td>

  </tr>

  <tr>

   <td width="365">+Car()+Car(String PlateNo,intyearmanufacture ,int monthmanufacture ,String color,double price,String manufactureby,guaranteedueyear int,guaranteeduemonth int)+getYearManufacture():int+getMonthManufacture():int+getColor():String+getPrice():double+setYearManufacture(int year):void+setMonthManufacture(int month):void+setColor(String color):void+setGuarantee(int month,int year):void+getCarAge():String+printCarInfo():String+getmanufactureby():String+getCalculateGuarantee():String</td>

  </tr>

 </tbody>

</table>

<strong>Class Driver for Palestinian Car Agency</strong>:

<h1>Note that</h1>

<ol>

 <li>getCarAge() method must calculate the age of car in years and months and return data as string type.</li>

 <li>getCalculateGuarantee() method should calculate the reaming years and months for guarantee.</li>

 <li>Guarantee date should contains the years and months remain for cars from current date.</li>

 <li>All Output string should be printed in UPPER case.</li>

 <li>print all information about cars with ages and guarantee due to inside class driver.</li>

</ol>

Write a <strong><em>driver class </em></strong>that creates an <strong>array </strong>of 5 [ do not create scanner, initialize them inside class driver ] Cars then passes the array to the two underneath methods :

<ol>

 <li><strong>public static void </strong>printCarsInfo( Car [ ] cars){</li>

</ol>

//print all information about cars with ages and guarantee due to.

}

<ol start="2">

 <li>a method named MaxPrice which will return the car object with the maximum price.</li>

</ol>

<strong>public static </strong>Car maxPrice( Car [ ] cars) {

}

<u>Set of instructions:</u>

1.Create folder at your desktop with your Assignment#, ID, and your name Example:A2_1190100_AliMohammad

<ol start="2">

 <li>Create a new project using Eclipse IDE and store your project inside this folder.</li>

</ol>

3.<strong>Zipped </strong>this folder and submit it by your ITC account [under meta course ].