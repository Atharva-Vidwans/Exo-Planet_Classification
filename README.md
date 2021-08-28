# Exo-Planet Classification<br>
<h3>The aim of this project is to Detect Exoplanets from light curves of Kepler Mission using FFT and Recurrence Plots and analyze to what extent they affect the accuracy of Exo-Planets Classification</h3>  
<br>
The quest for finding life and habitat in the universe other than earth has been going on since long. To uncover it, National Aeronautics and Space Administration (NASA) has Kepler Mission which captured data of brightness of stars which are called light curves. These are formed when a star transits from one place to another. This star could be an exoplanet and this is decided by checking its brightness. This data is in the form of time series format. Using this data, Support Vector Machine is applied. To improve the performance of models this research uses pre-processing techniques like Fast Fourier Transform and Recurrence plots before feeding the data to any models. Then models like Support Vector Machine and Transfer Learning with VGG16 are used. Different patterns were plotted and time series data was analysed to check if the data point is exoplanet or not. Lastly, the results after FFt and Recurrence Plots were compared with Time Series data. That is,the results for with and without pre processing techniques are compared and they show how FFT and Recurrence Plots make a difference in getting improved performance in terms of accuracy, precision, F1 score, etc.


<h3>Visualization of ExoPlanet and Non-ExoPlanet Data in Time Series, FFT and Recurrence Plots</h3>
<table>
<tr>
  
  <th scope="col">Method</th>
  <th scope="col">Positive Data</th>
  <th scope="col">Negative Data</th>
</tr>

<tr>
  <th scope="row">Time Series</th>
  <td><img src="/Images/Time_Pos.JPG" width="350" height="200"></td>
  <td><img src="/Images/Time_Neg.JPG" width="350" height="200"></td>
</tr>
  
<tr>
  <th scope="row">Recurrence Plot</th>
  <td><img src="/Images/Rec_Pos.JPG" width="350" height="350"></td>
  <td><img src="/Images/Rec_Neg.JPG" width="350" height="350"></td>
</tr>
  
<tr>
  <th scope="row">FFT</th>
  <td><img src="/Images/FFT_Pos.JPG" width="350" height="200"></td>
  <td><img src="/Images/FFT_Neg.JPG" width="350" height="200"></td>
</tr>

  
</table>

<br><br>
NOTE:<br>
Due to hardware limitations the data used for training purpose is just a small portion of total data. Due to this, the accuracy has dropped drastically. The accuracy of the models can be increased by considering more data. The aim was to analyse the effect of FFT and Recurrence Plots on the accuracy of Exo-Planet classification.   
