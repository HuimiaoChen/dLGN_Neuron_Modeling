(1)
FluoData_Fitting_plus_v2.ipynb
FluoData_Fitting_plus_v1.ipynb
FluoData_Fitting_plus_v0.ipynb
FluoData_Fitting_v1.ipynb
FluoData_Fitting_v0.ipynb

FluoData_Fitting_v1.ipynb is an update of FluoData_Fitting_v0.ipynb. FluoData_Fitting_v1.ipynb is a file including all basic regression methods: (a) Linear regression; (b) Power-law regression; (c) Exponential regression; (d) Logistic regression.

Note: Although FluoData_Fitting_v0.ipynb includes some example code that is not in FluoData_Fitting_v1.ipynb, this part of example code has been included in Example_Code_for_FluoData_Reseach.ipynb (see (3)).

FluoData_Fitting_plus_v0.ipynb only remains the Logistic regression from FluoData_Fitting_v1.ipynb because it is the best one in basic regressions. The "balanced weights" Logistic regression is not included in FluoData_Fitting_plus_v0.ipynb because of its poor performance. FluoData_Fitting_plus_v0.ipynb adds "Read fluorescence dFF structure data" (for a try to concatenate them but fails; this is further done in FluoData_Fitting_plus_v2.ipynb), "Decay restoration of red and trend visualization" and "Read pupil data", and can include decay restored data or/and pupil sizes in regression. The part "Analysis for pupil and fluorescence" in FluoData_Fitting_plus_v0.ipynb is not developed, which is done in FluoData_Fitting_plus_v1.ipynb.

FluoData_Fitting_plus_v1.ipynb adds things in "Analysis for pupil and fluorescence" and plots figures.

FluoData_Fitting_plus_v2.ipynb improves "Read fluorescence structure data" and plots figures, and adds "Extract the chronological order of randomized conditions and the sequences; extract the singal traces and tran and test".


(2)
FluoData_Analysis_local_v0.ipynb
FluoData_Analysis_v2.ipynb
FluoData_Analysis_v1.ipynb
FluoData_Analysis_v0.ipynb

All four are for 2p imgaing analysis. FluoData_Analysis_local_v0.ipynb is run locally on my own computer because images are too large to run on Google Colab; FluoData_Analysis_v2.ipynb, FluoData_Analysis_v1.ipynb, and FluoData_Analysis_v0.ipynb are run on Google Colab. FluoData_Analysis_v2.ipynb is an update of FluoData_Analysis_v1.ipynb and FluoData_Analysis_v0.ipynb. 

Note: Although FluoData_Analysis_v1.ipynb and FluoData_Analysis_v0.ipynb include some example code that is not in FluoData_Analysis_v2.ipynb, this part of example code has been included in Example_Code_for_FluoData_Reseach.ipynb (see (3)).

FluoData_Analysis_local_v0.ipynb can be viewed as a "FluoData_Analysis_v3.ipynb". Only need to focus on the stuff in FluoData_Analysis_local_v0.ipynb. Or if running on Google Colab, refer to FluoData_Analysis_v2.ipynb to see the difference for the code to run on Google Colab.


(3)
Example_Code_for_FluoData_Reseach.ipynb

Example_Code_for_FluoData_Reseach.ipynb is the example code for some basic operations. Code in this file is collected from the early version of above code files, like FluoData_Analysis_v1.ipynb, FluoData_Analysis_v0.ipynb, FluoData_Fitting_v0.ipynb. So the later versions of algorithm code don't include any example code so that they are clearer.

