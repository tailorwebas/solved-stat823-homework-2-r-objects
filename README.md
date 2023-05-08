Download Link: https://assignmentchef.com/product/solved-stat823-homework-2-r-objects
<br>
Launch RStudio and open a new RMarkdown file or use the class RMarkdown template provided and save it on your working directory as a .Rmd file. At the end of the activity, save your <strong>pdf </strong>generated from RMarkdown+Knitr and submit it in the Blackboard dropbox.

<strong>Show all your work</strong>. Late submission will attract a penalty of 10 points per day after the due date.

If you have questions, please post them on the lesson discussion board.

<ol>

 <li>(a) Create a vector of length 10 and fill it with a sequence of integers.</li>

</ol>

(b) Coerce the vector into a matrix of 5 rows and 2 columns. (c) Name the columns of the matrix “A” and “B”.

<ol start="2">

 <li>Assume that we have recorded the names and ages for four people: James is 27, Art is 42, Kate is 29, and Alex is 33.

  <ul>

   <li>Create a vector of names and a vector of ages from the data, making sure that you keep the ordering of the elements consistent.</li>

   <li>Use the class() function to print the class metadata R has stored for each vector.</li>

  </ul></li>

</ol>

<ul>

 <li>Using data.frame(), combine the two vectors into a dataframe and name the columns something informative. Print out the dataframe.</li>

</ul>

<ol start="3">

 <li>A hypothetical data with heights (in cm) and weights (in kg) of 10 family members are shown below:</li>

</ol>

height (cm)      weight (kg)

<table width="218">

 <tbody>

  <tr>

   <td width="95">Niece</td>

   <td width="79">120</td>

   <td width="44">22</td>

  </tr>

  <tr>

   <td width="95">Son</td>

   <td width="79">172</td>

   <td width="44">52</td>

  </tr>

  <tr>

   <td width="95">GrandPa</td>

   <td width="79">163</td>

   <td width="44">71</td>

  </tr>

  <tr>

   <td width="95">Daughter</td>

   <td width="79">158</td>

   <td width="44">51</td>

  </tr>

  <tr>

   <td width="95">Yai</td>

   <td width="79">153</td>

   <td width="44">51</td>

  </tr>

  <tr>

   <td width="95">GrandMa</td>

   <td width="79">148</td>

   <td width="44">60</td>

  </tr>

  <tr>

   <td width="95">Aunty</td>

   <td width="79">160</td>

   <td width="44">50</td>

  </tr>

  <tr>

   <td width="95">Uncle</td>

   <td width="79">170</td>

   <td width="44">67</td>

  </tr>

  <tr>

   <td width="95">Mom</td>

   <td width="79">155</td>

   <td width="44">53</td>

  </tr>

  <tr>

   <td width="95">Dad</td>

   <td width="79">167</td>

   <td width="44">64</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Create a vector called ‘ht’ corresponding to the heights of the 11 family members. Assign the names of the family<sub>10 </sub>members to the ‘names’ attribute of this vector.</li>

 <li>Create a vector called ‘wt’ corresponding to the family member’s weights.</li>

 <li>Compute the body mass index (BMI: units should be kg/<em><sub>m</sub></em><sup>2</sup>) of each person where BMI = weight/height<sup>2</sup>.</li>

 <li>Identify the persons who have the lowest and highest BMI and calculate the standard deviation of the BMI.</li>

</ul>