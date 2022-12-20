# Hi-C-Analysis-Using-Numerical-Linear-Algebra
Final Project in the course of Numerical Linear Algebra at Skoltech ("Hi" team; Kirill Ulianov, Marina Morozova, Maksim Grigoryan, Shamil Magomedov). The project is dedicated to Hi-C matrix analysis using eigendecompositions.

We implemented classic approach described by Imakaev ([1], Hi-C_Eigendecomposition.ipynb) in which first eigenvector is used to localise active/inactive chromatine compartments and repeated Gaussian Network Model ([2], HI_C_Gaussian_network_model.ipynb) that in contrast to classic approach utilizes all eigenvectors to localize chromatine domains. Algorithm_comparison.ipynb contains comparison of the approaches in relation to the prediction of gene activity. 

[1] M. Imakaev, G. Fudenberg, R. P. McCord, N. Naumova, A. Goloborodko, B. R. Lajoie, J. Dekker, and L. A. Mirny, “Iterative correction of hi-C data reveals hallmarks of chromosome organization,” Nature Methods, vol. 9, no. 10, pp. 999–1003, 2012. 

[2] N. Sauerwald, S. Zhang, C. Kingsford, and I. Bahar, “Chromosomal dynamics predicted by an elastic network model explains genome-wide accessibility and long-range couplings,” Nucleic Acids Research, vol. 45, no. 7, pp. 3663–3673, 2017. 
