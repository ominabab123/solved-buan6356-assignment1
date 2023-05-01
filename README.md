Download Link: https://assignmentchef.com/product/solved-buan6356-assignment1
<br>



<ol>

 <li>Create an R Markdown document to prepare your answers. You should upload <strong>two (2)</strong> files on eLearning: (i) an <strong>.RMD</strong> file; and (ii) a <strong>.PDF</strong> file that is generated using “knit” in the .RMD file.  Both of these files should contain the required R code, R tables and charts, and all the required explanations and answers to the questions in the homework.</li>

 <li>Include your name at the top of the file.</li>

</ol>

<ol start="3">

 <li><strong>DO NOT</strong> use an absolute directory path. I should be able to “knit” your R Markdown document to an .html/.pdf document without trying to find the input data in another directory.  Test the “knit” process before uploading files on eLearning.  Assume that I have the .csv file(s) mentioned below.</li>

 <li><strong>DO NOT</strong> change the dataset name before importing it into R. If you rename the dataset or any variable(s), use your R script to do that.</li>

 <li>Label the charts appropriately. I should be able to figure out what information a chart is providing by looking at the chart title and its labels.</li>

 <li>Any assignment submitted after the deadline will be considered late and will not be graded.</li>

</ol>




<u>Homework 1</u>

The “Utilities” dataset includes information on 22 public utility companies in the US.  The variable definitions are provided below.




Fixed_charge = fixed-charge covering ratio (income/debt)

RoR = rate of return on capital

Cost = cost per kilowatt capacity in place

Load_factor = annual load factor

Demand_growth = peak kilowatthour demand growth from 1974 to 1975

Sales = sales (kilowatthour use per year)

Nuclear = percent nuclear

Fuel_Cost = total fuel costs (cents per kilowatthour)

<u>For <strong>Questions 1-4 </strong>below, do not scale the data.</u>

<ol>

 <li>Compute the minimum, maximum, mean, median, and standard deviation for each of the numeric variables using data.table package. Which variable(s) has the largest variability?  Explain your answer.</li>

 <li>Create boxplots for each of the numeric variables. Are there any extreme values for any of the variables?  Which ones?  Explain your answer.</li>

 <li>Create a heatmap for the numeric variables. Discuss any interesting trend you see in this chart.</li>

 <li>Run principal component analysis using <em>unscaled numeric variables</em> in the dataset. How do you interpret the results from this model?</li>

 <li>Next, run principal component model after <em>scaling the numeric variables</em>. Did the results/interpretations change?  How so?  Explain your answers.</li>

</ol>