# Cluster-based control (CBC)

This is a repository containing MATLAB codes for the paper: 
Nair et al., "Cluster-based feedback control of turbulent post-stall separated flows", JFM, 2019. 
Please cite this work when using the codes.

main_CBC.m : Computes cluster-centroids using aerodynamic trajectories and deduces optimal cluster-based control laws. 
       
src : Computes the cluster-based reduced order model. For details refer to Kaiser et al., Cluster-based reduced-order modelling of a mixing layer, JFM 2014. Please also cite this work.

To run this code, a Navier-Stokes solver is needed (run_Navier_Stokes) in CBC.m. 



