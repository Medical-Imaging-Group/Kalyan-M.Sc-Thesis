# Kalyan M.ScThesis
Kalyan M.Sc Thesis
The following MATLAB programs were used as a part of MSc.(Engg.) thesis submitted.

**Thesis Title**: Development and Validation of Analytical Models for Diﬀuse Fluorescence Spectroscopy/Imaging in Regular Geometries.

[Kalyan MSc Thesis](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxzZXJjbWlnfGd4OjcyOTNmYjUwZGI0YTc2NWM)

Matlab Based Programs (Requires [NIRFAST](http://www.dartmouth.edu/~nir/nirfast/)):

1.Source file for Circular Geometry.
     - GetPhase.m <br/>
     - avg_out_values_circle.m
     _ fem_amp_phase_Circle.m
     _ load_fem_data_Circle.m
     _ src_det_dist_Circle.m
     _ analytical_MTOF_Circle.m
     _  analytical_data_Circle.m
     _ fdot_Circle.m
     
   1.Source file for Cube Geometry.
     _ avg_out_values.m<br/>
     _ load_fem_data_Cube.m
     _ fem_amp_phase_Cube.m
     _ analytical_data_Cube.m
     _ src_det_dist_Cube.m
     _ fdot_Cube.m
     
   2.Source file for Semi-Infinite Geometry approximation using Slab.
     _ fem_amp_phase_Slab.m
     _ avg_out_values.m
     _ load_fem_data_Slab.m
     _ analytical_data_Slab.m
     _ src_det_dist_Slab.m
     _ dot_Slab.m
     _ analytical_MTOF_Slab.m
     
3.Source file for Cylindrical Geometry.
     _ fem_amp_phase_Cylinder.
     _ avg_out_values_Cylinder.m
     _ load_fem_data_Cylinder.m
     _ src_det_dist_Cylinder.m
     _ fdot_Cylinder.m
     _ analytical_data_Cylinder.m
     
  1. Source file for Spherical Geometry.
     _ src_det_dist_Sphere.m
     _ fem_amp_phase_Sphere.m
     _ avg_out_values_Sphere.m
     _ load_fem_data_Sphere.m
     _ analytical_MTOF_Sphere.m
     _ fdot_Sphere.m
     _ analytical_data_Sphere.m
     
  2.Source file for MTOF calculation.
    _ save_trdata.m
    _ load_trdata.m
    _ TR_data.m
    _ TPSF.m
    _ plot_mtof.m
    _ fem_MeanTimeOfFlight.m
    _ Tau_Vary.m
    _ AllGeom_MTOF.m
    
4.Source file for Patient Mesh.
    _ fem_amp_phase_pat.m
    _ avg_out_values.m
    _ load_fem_data_pat.m
    _ analytical_data_pat.m
    _ uniform_fl_mesh.m
    _ convert_fl_mesh.m
    _ fdot_pat.m
    
5.Files performing generic functions.
    _ run_simulations.m
    _ TOF_plots.m
    _ params.m
    _ setup.m
    _ meshes.m
    _ Flux_plots.m
    _ MTOF_plots.m
    _ get_brs_rad.m
    _ Cube_PAT.m
    
6. Meshes to verify the fluorescence computation in NIRFAST.
   1.Directory Structure for source o be integrated in NIRFAST.
