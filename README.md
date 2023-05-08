Download Link: https://assignmentchef.com/product/solved-sml-assignment-5-decision-trees-bagging-random-forest
<br>



<ul>

 <li><strong>Dataset:</strong></li>

</ul>

The attached dataset is about PM2.5.

<strong>Training Data:</strong> Two alternate years can be taken as train data.​

<strong>Testing Data:</strong> Two years of data from the remaining three can be taken as test data.​




<ul>

 <li><strong>Problem Statement:</strong></li>

</ul>




You are supposed to perform two tasks for this dataset: <strong>Classification</strong>​ and ​ <strong>Regression</strong>​

<ol>

 <li><strong>Classification Task: </strong>Target Column: “Month”</li>

</ol>

Evaluation Metric: Accuracy




<ol start="2">

 <li><strong>Regression Task: </strong>Target Column: “PM2.5”</li>

</ol>

Evaluation Metrics: MSE

Also, report the mean and standard deviation of the error.

<strong> </strong>

Implement the above problem statement(both for Classification and Regression) from scratch using the following:

<ol>

 <li><strong>Decision Trees (DT) – </strong>(​ You have to analyze yourself as told in class for different depths, width and other parameters of the tree and draw your inferences.)</li>

 <li><strong>Bagged Decision Trees </strong></li>

</ol>

<ul>

 <li><strong>Random Forest</strong></li>

</ul>




Implement these as taught in the class.




<ul>

 <li><strong>Gaussian Processes: </strong></li>

</ul>

<strong> </strong>

In the data provided to you, you will find signal strength in dB vs distance. Assume the “<strong>Distance</strong>​ ”​ to be an independent variable and “<strong>Signal</strong>​<strong> Strength</strong>”​ as a target. Compute the mean and variance prediction for signal strength at the following 5 points {Sr. No.: &lt;2,4,6,8,10&gt;}. Use GPR to train using the remaining data points {Sr. No.: &lt;1,3,5,7,9,11,12&gt;} from the table provided.




<table width="255">

 <tbody>

  <tr>

   <td width="60">Sr. No.</td>

   <td width="77">Distance</td>

   <td width="118">Signal Strength(DBM)</td>

  </tr>

  <tr>

   <td width="60">1</td>

   <td width="77">0</td>

   <td width="118">-45</td>

  </tr>

  <tr>

   <td width="60">2</td>

   <td width="77">1</td>

   <td width="118">-51</td>

  </tr>

  <tr>

   <td width="60">3</td>

   <td width="77">2</td>

   <td width="118">-58</td>

  </tr>

  <tr>

   <td width="60">4</td>

   <td width="77">3</td>

   <td width="118">-63</td>

  </tr>

  <tr>

   <td width="60">5</td>

   <td width="77">4</td>

   <td width="118">-36</td>

  </tr>

  <tr>

   <td width="60">6</td>

   <td width="77">5</td>

   <td width="118">-52</td>

  </tr>

  <tr>

   <td width="60">7</td>

   <td width="77">6</td>

   <td width="118">-59</td>

  </tr>

  <tr>

   <td width="60">8</td>

   <td width="77">7</td>

   <td width="118">-62</td>

  </tr>

  <tr>

   <td width="60">9</td>

   <td width="77">8</td>

   <td width="118">-36</td>

  </tr>

  <tr>

   <td width="60">10</td>

   <td width="77">9</td>

   <td width="118">-43</td>

  </tr>

  <tr>

   <td width="60">11</td>

   <td width="77">10</td>

   <td width="118">-55</td>

  </tr>

  <tr>

   <td width="60">12</td>

   <td width="77">11</td>

   <td width="118">-64</td>

  </tr>

 </tbody>

</table>


