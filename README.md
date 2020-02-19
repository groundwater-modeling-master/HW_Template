# Homework 1 - Box Model

I recommend you start by walking through the self check exercise contained in this repo. The exercise is described in the README of that directory and an IPython notebook and a solution key are also provided.

----
### Assignment
Build a steady state box model.  The model should have 25x25 cells, each 100 m in x and in y.  There is one layer, 10 m thick.  The medium is homogeneous with K = 1.0 m/day in x and y and 0.1 m/day in z.  The porosity is 0.35, specific yield is 0.3, and storage coefficient is 0.001.  The right boundary is constant flow with a total of 25 m3/day entering the domain.  The left boundary is a constant head of 7 m relative to the datum, which is located at the bottom of the domain.

The head should no longer vary linearly across the domain.  Describe the slope of the water table as a function of distance from the left boundary – in particular, does the water table slope increase or decrease with distance from the left boundary.  Then, explain why the water table has this general slope.  Be sure to include concepts of steady state flow and saturated thickness (distance from the water table to the base of the aquifer - the thickness through which water is flowing).

----
### Submission instructions
You should build and run your model in the **Assignment** folder. When you are ready to submit you should copy the following 3 items into the **Submission** folder for grading.

1. A pdf document titled **LastName_HW1_Summary.pdf** which has your written answers to the questions along with any graphs which support your case. This should be a complete document that summarizes your solution without referring to the Ipython notebook.   

2. IPython notebook with your model and analysis **LastName_HW1.ipynb**.

3. Export of your final notebook as a pdf with the same name in the assignment folder (e.g. **LastName_HW1.pfb**).


---
### How to export your notebook as pdf
Make sure you clean up any intermediate outputs and confirm it is all running before you create your final export. You can do this with the following steps:
  - Click “Cell > All Output > Clear”
  - Click “Kernel > Restart & Run All”
  - Wait for your code cells to finish executing and check they did so as expected
  - Once this is done you can export to pdf two ways:
  1. Go to File- Print Preview and then save your print preview as a  pdf.
  2. If you have setup the pdf conversion options for Jupyter (see the getting started instructions in the Course Materials repo) then you can also convert to pdf with the  following command line argument: `jupyter nbconvert --to pdf MyNotebook.ipynb`
