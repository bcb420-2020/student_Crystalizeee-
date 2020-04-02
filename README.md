# student_Crystalizeee
Dong Hoon Han

[**Link to the Wiki**](https://github.com/bcb420-2020/student_Crystalizeee-/wiki)<br>

Html file can be directly clicked to be downloaded, or click on link to view on web browser.

[**Link to Assignment 1**](https://htmlpreview.github.io/?https://github.com/bcb420-2020/student_Crystalizeee-/blob/master/Assignment_1_Data_Pre_Processing.html)<br>


[**Link to Assignment 2**](https://htmlpreview.github.io/?https://github.com/bcb420-2020/student_Crystalizeee-/blob/master/Assignment_2_TORA.html)<br>
*For assignment 2, please compile using the Assignment2.Rmd and library2.bib files.*


<br><br>
[**Link to Assignment 3**](https://htmlpreview.github.io/?https://github.com/bcb420-2020/student_Crystalizeee-/blob/master/A3_DongHan.html#enrichment_map_in_cytoscape)<br><br>

*For assignment 3, please compile using <br>
**A3_DongHan.Rmd** <br>
**library3.bib** <br>
**Images** directory <br>
in the same directory <br>
using the docker image pulled by the bash command below*

**sudo docker pull risserlin/em_base_image:latest**
<br><br>
Warning: this will take a while to compile because I am running 2 GSEAs from the notebook.
<br><br>
**Compile Command:**
<br><br>
sudo docker run --rm -it -v "$(pwd)":/home/rstudio/projects --user rstudio risserlin/em_base_image:latest /usr/local/bin/R -e "rmarkdown::render('/home/rstudio/projects/A3_DongHan.Rmd',output_file='/home/rstudio/projects/A3_DongHan.html')" > processing_output_filename
