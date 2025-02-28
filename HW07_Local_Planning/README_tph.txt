List of components：

angle3pt: 			Calculates angle by turning from a to c around b.
calc_ax_profile: 		Calculate the longitudinal acceleration profile for a given velocity profile.
calc_head_curv_an: 		Analytical curvature calculation on the basis of third order splines.
calc_head_curv_num: 	Numerical curvature calculation.
calc_normal_vectors: 	Calculate normalized normal vectors on the basis of headings psi (psi - pi/2).
calc_normal_vectors_ahead: 	Calculate normalized normal vectors on the basis of headings psi (psi + pi/2).
calc_spline_lengths:	 	Calculate spline lengths.
calc_splines: 		Calculate splines for a (closable) path.
calc_t_profile: 		Calculate the temporal duration profile for a given velocity profile.
calc_tangent_vectors: 	Calculate normalized tangent vectors on the basis of headings psi.
calc_vel_profile: 		Calculate velocity profile on the basis of a forward/backward solver. Important: ax_max_machines input must be inserted without drag resistance, i.e. simply by calculating F_x_drivetrain / m_veh
calc_vel_profile_brake: 	Calculate velocity profile on the basis of a pure forward solver.
check_normals_crossing: 	Check if normal vectors of a given track have at least one crossing.
conv_filt: 			Filter a given signal using a 1D convolution (moving average) filter.
create_raceline: 		Function to create a raceline on the basis of the reference line and an optimization result.
get_rel_path_part: 		Get relevant part of a given path on the basis of a s position and a specified range.
import_veh_dyn_info: 	Imports the required vehicle dynamics information from several files: ggv and ax_max_machines.
import_veh_dyn_info_2: 	Imports local gg diagrams, required for local friction consideration.
interp_splines: 		Interpolate splines to get points with a desired stepsize.
interp_track: 		Interpolate track to get points with a desired stepsize.
interp_track_widths: 		Interpolation function for track widths.
iqp_handler: 		Handler function to iteratively call the minimum curvature optimization.
nonreg_sampling: 		Function to sample in non-regular intervals (based on curvature) from a given track.
normalize_psi: 		Normalize heading psi such that the interval [-pi, pi[ holds.
opt_min_curv: 		Minimum curvature optimization.
opt_shortest_path: 		Shortest path optimization.
path_matching_global: 	Match own vehicle position to a global (i.e. closed) path.
path_matching_local: 	Match own vehicle position to a local (i.e. unclosed) path.
progressbar: 		Commandline progressbar (to be called in a for loop).
side_of_line: 		Function determines if a point is on the left or right side of a line.
spline_approximation: 	Function used to obtain a smoothed track on the basis of a spline approximation.