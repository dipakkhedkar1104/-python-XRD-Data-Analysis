# My Project

 <p> In this project we proficiently utilized Python libraries such as NumPy, Pandas, Matplotlib and Pymatgen for data
manipulation, analysis and visualization. The project involved pre-processing XRD data, identifying
crystallographic peaks using peak-finding algorithms, determining crystal structures, d-spacing of Zn Nano powder.
Successfully extracted lattice parameters and other crystallographic information. The project not only demonstrated
Python programming and pymatgen library but also showcased a deep understanding of XRD techniques and
material science principles, providing valuable insights into the crystallographic properties of materials.</p>

## Screenshots
- ## XRD Data Of Zn Nano-Powder
  <p>Using pandas library we loaded the our data.csv file which containes numeric data for theta and intensity parameters which required to plot XRD pattern.</p>
  
![DATA](https://github.com/dipakkhedkar1104/-python-XRD-Data-Analysis/blob/main/image.png)

- ## Plot Of XRD Pattern
 <p> Here, we identified the peaks and mark them with * so we can easily identify peaks from the graph which is above the given set values for height and from that get effecient and accurate values for the further calculations.</p>
 
![Plot1](https://github.com/dipakkhedkar1104/-python-XRD-Data-Analysis/blob/main/Images/image.png)

- ## Calculate d-Spacing, Lattice parameters (a,b,c) and FWHM
 <p> Here is the graph from which we calculate the FWHM (full width half maxima), for that we mark vertical straigth line and then calculate the difference between two line i.e is our value for FWHM which required for further calculations.</p>
 
 ![Plot1](https://github.com/dipakkhedkar1104/-python-XRD-Data-Analysis/blob/main/Images/fwhm_plot.jpg)
 
 <p> Here, we find corresponding hkl values and from that we calculated the d-spacing for perticular peak using formula 1/d2 = (h^2 + k^2 + l^2).</p>
 <p> After d-spacing we calculate the approx. values of lattice parameter i.e a,b and c. </p>
 
![Plot1](https://github.com/dipakkhedkar1104/-python-XRD-Data-Analysis/blob/main/Images/FWHM_Grain_size_abc.jpg)



