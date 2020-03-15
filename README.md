# init_c_pbl
PLUTO twin jet 3D RMHD arrangement by Theo, Chistmas/NewYear 2019/20.

During vacation 2019-20, we managed to run twin jet arrangement emanating from the centre of the XYZ Cartesian grid. Only B is not precessing, others are. Next step is perhaps to convert the params that describe the system components (accr. disk wind, companion wind, densities, jet speed, precession angle, precession speed, etc etc, to params in pluto.ini, so that these do not need to be altered in the code. Yet again, this might limit code's generality. 

This whole thing is essentially a setup for initial/boundary conditions in PLUTO, that allows to run the simulation of precessing twin jets in RMHD format. 

This then is imaged with visit, then relativistically imaged with RLOS, including the capability to having calced neutrino emissivities in nemiss_pload4d. Either focused beam, or parallel rays, either head-on or from the side! It all essentially works by now (150320) and it is undergoing testing, during the lockdown!
