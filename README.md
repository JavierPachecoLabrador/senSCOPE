# senSCOPE
This repository containts the code of the senSCOPE model (Pacheco-Labrador et al., 2020), the new version 1.73.2, the code 
for the multiple-constraint inversion approach method (Pacheco-Labrador et al., 2019) adapted for the inversion senSCOPE: 
senSCOPE_MCinv (not yet updated to version 1.73).

senSCOPE v1.73.2 (Pacheco-Labrador et al., 2021) is a modified version of the Soil Canopy Observation, Photochemistry and 
Energy fluxes (SCOPE, Van der Tol at al. 2009) model. It includes new features and some corrections respect to the original version
and mainly developped over the SCOPE code version 1.73 (see Pacheco-Labrador et al., 2020). The main feature is the inclussion of
specific absopriton coefficients from Pacheco-Labrador et al., 2021 and Proctor et al., 2017 (also available in GitHub: 
https://github.com/drproctorWindsor/DecompositionPigments)
The present version is coordinated with the original SCOPEcode for consistency. senSCOPE adapts radiative transfer and plant 
function processes to represent canopies featuring mixed green and senesced leaves.

For general information about the functioning of SCOPE, check:
  Manual is available at ReadTheDocs https://scope-model.readthedocs.io/en/latest/ 

Information about senSCOPE can be found in the Documentation_senSCOPE_1.73.2.pdf included with the code

Information aobut senSCOPE_MCinv can be found in the Documentation_senSCOPE_MCinv-1.02 included with the code. Notice that this code has not
yet been adpated to the version 1.73.2 of senSCOPE.


If you use this code, please cite:
  * Pacheco-Labrador, J., El-Madany, T.S., van der Tol, C., Martin, M.P., Gonzalez-Cascon, R., Perez-Priego, O., Guan, J., Moreno, G., Carrara, 
      A., Reichstein, M., & Migliavacca, M. (2021). senSCOPE: Modeling mixed canopies combining green and brown senesced leaves. Evaluation in a 
      Mediterranean Grassland. Remote Sensing of Environment, 257, 112352
 
Useful references:
  * Pacheco-Labrador, J., El-Madany, T.S., van der Tol, C., Martín, M.P., Gonzalez-Cascon, R., Perez-Priego, O., Guan, J., Moreno, G., Carrara, A., 
      Reichstein, M., & Migliavacca, M. (2020). senSCOPE: Modeling radiative transfer and biochemical processes in mixed canopies combining green and senescent
      leaves with SCOPE. bioRxiv, 2020.2002.2005.935064
  * Pacheco-Labrador, J., Perez-Priego, O., El-Madany, T.S., Julitta, T., Rossini, M., Guan, J., Moreno, G., Carvalhais, N., Martín, M.P., Gonzalez-Cascon, R.,
      Kolle, O., Reischtein, M., van der Tol, C., Carrara, A., Martini, D., Hammer, T.W., Moossen, H., & Migliavacca, M. (2019). Multiple-constraint inversion of 
      SCOPE. Evaluating the potential of GPP and SIF for the retrieval of plant functional traits. Remote Sensing of Environment, 234, 111362    
  * Proctor, C., Lu, B., & He, Y. (2017). Determining the absorption coefficients of decay pigments in decomposing monocots. Remote Sensing of Environment, 199, 137-153
  * van der Tol, C., Verhoef, W., Timmermans, J., Verhoef, A., & Su, Z. (2009). An integrated model of soil-canopy spectral radiances, photosynthesis, fluorescence,
     temperature and energy balance. Biogeosciences, 6, 3109-3129
