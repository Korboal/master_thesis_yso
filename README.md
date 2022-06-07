# master_thesis_yso
Supplementary material for master thesis

**LPV:**

PDFs and output tables are located in the appropriate folders. Three different files for tables exist: they are all the same table just with different file extensions. LPV table includes all 811 analysed files.

**LAV:**

Due to the amount of stars in the LAV sample, the tables are too big for GitHub. The tables and output PDFs can be accessed in following links. Tables are the same just with different extension. They include all analysed 133717 stars. However, please only use the stars that were marked as "True" for column "good_sed".

* LAV YSO sample output PDFs in a zip file [7.26 GB] - https://drive.google.com/file/d/1zBmQ-QL6Wuf7PEe1OZUEh4C1Htc44fUn/view?usp=sharing
* LAV YSO sample .fits table [65 MB] - https://drive.google.com/file/d/1oa5M7ReulgbVmSNugxSEkAIdmZVVkdQo/view?usp=sharing
* LAV YSO sample .txt table [159 MB] - https://drive.google.com/file/d/1vr5worX65cJofhFoCYCXR17OVUoYnULi/view?usp=sharing
* LAV YSO sample .html table [135 MB] - https://drive.google.com/file/d/1Xt4h72dAk1C1f328iQQYfXgwVp1BNjjn/view?usp=sharing

**LPV table column description**

g2 indicates that the column is taken from Gaia DR2 database.
ge3 indicates that the column is taken from Gaia EDR3 database.
simbad indicates that the information was obtained from simbad.

1) source_id_g2 - Unique source identifier (unique within a particular Data Release) 
2) phot_g_mean_mag_g2 - G-band mean magnitude
3) phot_bp_mean_mag_g2 - Integrated BP mean magnitude
4) phot_rp_mean_mag_g2 - Integrated RP mean magnitude
5) radial_velocity_g2 - Radial velocity
6) radial_velocity_error_g2 - Radial velocity error
7) abs_mag_bol_g2 - Absolute bolometric magnitude of the star
8) abs_mag_bol_error_g2 - Error of absolute bolometric magnitude
9) rsg_flag_g2 - Red supergiant flag
10) bolometric_corr_g2 - Bolometric correction for LPVs
11) bolometric_corr_error_g2 - Error of the bolometric correction
12) frequency_g2 - Frequency of the LPV
13) frequency_error_g2 - Error on the frequency
14) a_g_val_g2 - line-of-sight extinction in the G band, A_G)
15) a_g_percentile_lower_g2 - aGVal lower uncertainty
16) a_g_percentile_upper_g2 - aGVal upper uncertainty
17) lum_val_g2 - stellar luminosity
18) lum_percentile_lower_g2 - lumVal lower uncertainty
19) lum_percentile_upper_g2 - lumVal upper uncertainty
20) radius_val_g2 - stellar radius
21) radius_percentile_lower_g2 - radiusVal lower uncertainty
22) radius_percentile_upper_g2 - radiusVal upper uncertainty
23) rv_template_teff_g2 - Teff of the template used to compute radial velocity
24) teff_val_g2 - stellar effective temperature
25) teff_percentile_lower_g2 - teffVal lower uncertainty
26) teff_percentile_upper_g2 - teffVal upper uncertainty
27) source_id_ge3 - Unique source identifier (unique within a particular Data Release)
28) ra_ge3 - Right ascension
29) dec_ge3 - Declination
30) l_ge3 - Galactic longitude
31) b_ge3 - Galactic latitude
32) parallax_ge3 - Parallax
33) parallax_error_ge3 - Standard error of parallax
34) pmra_ge3 - Proper motion in right ascension direction
35) pmra_error_ge3 - Standard error of proper motion in right ascension direction
36) pmdec_ge3 - Proper motion in declination direction
37) pmdec_error_ge3 - Standard error of proper motion in declination direction
38) phot_g_n_obs_ge3 - Number of observations contributing to G photometry
39) phot_g_mean_flux_ge3 - G-band mean flux
40) phot_g_mean_flux_erro_ge3 - Error on G-band mean flux
41) phot_bp_n_obs_ge3 - Number of observations contributing to BP photometry
42) phot_g_mean_mag_ge3 - G-band mean magnitude
43) phot_bp_mean_flux_ge3 - Integrated BP mean flux
44) phot_bp_mean_flux_error_ge3 - Error on the integrated BP mean flux
45) phot_bp_mean_mag_ge3 - Integrated BP mean magnitude
46) phot_rp_n_obs_ge3 - Number of observations contributing to RP photometry
47) phot_rp_mean_flux_ge3 - Integrated RP mean flux
48) phot_rp_mean_flux_error_ge3 - Error on the integrated RP mean flux
49) phot_rp_mean_mag_ge3 - Integrated RP mean magnitude
50) astrometric_n_good_obs_al_ge3
51) astrometric_gof_al_ge3
52) astrometric_chi2_al_ge3
53) astrometric_excess_noise_ge3
54) astrometric_excess_noise_sig_ge3
55) astrometric_params_solved_ge3
56) pseudocolour_ge3
57) pseudocolour_error_ge3
58) visibility_periods_used_ge3
59) ruwe_ge3
60) duplicated_source_ge3 
61) main_id_simbad - Name in SIMBAD from 1.65 arcsec cross-match
62) main_type_simbad - Star type in SIMBAD
63) other_type_simbad - All other types of star in SIMBAD
64) simbad_yso - YSOs identified in SIMBAD (main or other type)
65) simbad_cand_yso - Only candidates YSO in SIMBAD (main or other type)
66) simbad_not_yso_or_cand - Not SIMBAD YSO or YSO cand. (main or other type)
67) angDist_simbad - Xmatch distance in arcseconds
68) mir_exists - Whether least 2 points exist beyond 2.2 micrometers
69) last_wv - Wavelength of the filter with the longest wavelength [m]
70) last_ratio_err - Error of ratio of the last filter
71) last_ratio - Ratio of the last filter
72) biggest_ratio_err - Error of the biggest ratio
73) biggest_ratio_wv - Wavelength of the filter with the biggest ratio [m]
74) biggest_ratio - Ratio of the filter with the biggest ratio
75) last_wv_mir - Wavelength of the filter with the longest wavelength shorter than 25 micrometers [m]
76) last_ratio_err_mir - Error of ratio of the last filter shorter than 25 micrometers
77) last_ratio_mir - Ratio of the last filter shorter than 25 micrometers
78) biggest_ratio_err_mir - Error of the biggest ratio shorter than 25 micrometers
79) biggest_ratio_wv_mir - Wavelength of the filter with the biggest ratio shorter than 25 micrometers [m]
80) biggest_ratio_mir - Ratio of the filter with the biggest ratio shorter than 25 micrometers
81) slope_25 - Spectral index 2.2 to 25 micrometers
82) slope_error_25 - St.dev. of spectral index 2.2 to 25 micrometers
83) slope_25_yso_class - Class based on spectral index 2.2 to 25 micrometers
84) slope_20 - Spectral index 2.2 to 20 micrometers
85) slope_error_20 - St.dev. of spectral index 2.2 to 20 micrometers
86) slope_20_yso_class - Class based on spectral index 2.2 to 20 micrometers
87) integrated_excess - Value of integrated IR excess between Rayleigh-Jeans regime and intra-, extrapolation of SED between 4 and 25 micrometers
88) period_gaia_g - Fitted period of Gaia G [days]
89) max_amp_gaia_g - Max amplitude of Gaia G light curve [mag]
90) q95_m_q5_gaia_g - Q95 - Q5 of Gaia G light curve [mag]
91) st_dev_gaia_g - St. dev. of Gaia G light curve [mag]
92) avg_err_gaia_g - Average error of Gaia G light curve data points [mag]
93) amp_fit_gaia_g - Amplitude of the light curve fit for Gaia G [mag]
94) points_gaia_g - Amount of data points in Gaia G light curve
95) skewness_gaia_g - Skewness of Gaia G light curve
96) total_obs_time_gaia_g - Total observational time between first and last Gaia G measurement [days]
97) points_gaia_bp - Amount of data points in Gaia BP light curve
98) points_gaia_rp - Amount of data points in Gaia RP light curve
99) gaia_g_ls_fap - False alarm probability Gaia G light curve
100) period_ztf_g - Fitted period of ZTF g [days]
101) points_ztf_g - Amount of data points in ZTF g
102) period_ztf_r - Fitted period of ZTF r [days]
103) points_ztf_r - Amount of data points in ZTF r
104) period_ztf_i - Fitted period of ZTF i [days]
105) points_ztf_i - Amount of data points in ZTF i
106) max_amp_ztf_g - Max amplitude of ZTF g [mag]
107) q95_m_q5_ztf_g - Q95 - Q5 of ZTF g [mag]
108) st_dev_ztf_g - St. dev. of ZTF g [mag]
109) avg_err_ztf_g - Average error of ZTF g data points [mag]
110) max_amp_ztf_r - Max amplitude of ZTF r [mag]
111) q95_m_q5_ztf_r - Q95 - Q5 of ZTF r [mag]
112) st_dev_ztf_r - St. dev. of ZTF r [mag]
113) avg_err_ztf_r - Average error of ZTF r data points [mag]
114) max_amp_ztf_i - Max amplitude of ZTF i [mag]
115) q95_m_q5_ztf_i - Q95 - Q5 of ZTF i [mag]
116) st_dev_ztf_i - St. dev. of ZTF i [mag]
117) avg_err_ztf_i - Average error of ZTF i data points [mag]
118) amp_fit_ztf_g - Amplitude of the light curve fit for ZTF g [mag]
119) amp_fit_ztf_r - Amplitude of the light curve fit for ZTF r [mag]
120) amp_fit_ztf_i - Amplitude of the light curve fit for ZTF i [mag]
121) band_mean_ztf_g - Band mean of ZTF g [mag]
122) band_mean_ztf_r - Band mean of ZTF r [mag]
123) band_mean_ztf_i - Band mean of ZTF i [mag]
124) skewness_ztf_g - Skewness of ZTF g
125) skewness_ztf_r - Skewness of ZTF r
126) skewness_ztf_i - Skewness of ZTF i
127) total_obs_time_ztf_g - Total observational time between first and last ZTF g measurement [days]
128) total_obs_time_ztf_r - Total observational time between first and last ZTF r measurement [days]
129) total_obs_time_ztf_i - Total observational time between first and last ZTF i measurement [days]
130) ztf_g_ls_fap - False alarm probability ZTF g
131) ztf_r_ls_fap - False alarm probability ZTF r
132) gaia_g_snr - Signal to noise ratio of Gaia G fitted peak in periodogram
133) ztf_g_snr - Signal to noise ratio of ZTF g fitted peak in periodogram
134) ztf_r_snr - Signal to noise ratio of ZTF r fitted peak in periodogram
135) gaia_g_gof - Goodness of fit of fitted period based on normalised periodogram for Gaia G
136) ztf_g_gof - Goodness of fit of fitted period based on normalised periodogram for ZTF g
137) ztf_r_gof - Goodness of fit of fitted period based on normalised periodogram for ZTF r
138) light_curve_fitting_flag - Flag indicating what type of light curve fit was done (Type I-IV)
139) sfr_name - Name of star-forming region based on visual location and parallax
140) confidence_sfr - Closer location visually results in higher confidence (0 to 1, 1 indicating being very close to centre, and 0 not being part of any SFR)
141) similar_to_sfr_pm - Whether a star is within 5 sigmas of the SFR's stars' median proper motion (yes, no, ??; ?? - means that no information on SFR's PM is available)
142) not_yso_sample - Stars that are red giants in HR diagram and lack IR excess (True/False)
143) yso_sample - Reduced sample. Either located within YSO part of HR diagram or have IR excess (True/False)
144) ir_excess_criteria - YSO identified by having IR excess (True/False)
145) sfr_criteria - YSO identified by being within SFR and having same PM if applicable (True/False)
146) yso_based_on_either_criteria - YSO identified based on either having IR excess or location within SFR (True/False)
147) yso_based_on_both_criteria - YSO identified by having both IR excess and located within SFR (True/False)

**LAV table column descriptions**

all Gaia data is obtained from GEDR3
simbad indicates that the information was obtained from simbad.

1) source_id - GEDR3 source ID
2) ra
3) dec
4) parallax_mas
5) parallax_error_mas
6) pmra_masperyr
7) pmra_error_masperyr
8) pmdec_masperyr
9) pmdec_error_masperyr
10) visibility_periods_used
11) ruwe
12) phot_g_n_obs
13) phot_g_mean_mag
14) phot_bp_n_obs
15) g_mean_mag_err
16) phot_bp_mean_mag
17) phot_rp_n_obs
18) bp_mean_mag_err
19) phot_rp_mean_mag
20) rp_mean_mag_err
21) phot_bp_rp_excess_factor
22) DR2_LPV
23) isDR2var
24) last_wv - Wavelength of the filter with the longest wavelength [m]
25) last_ratio_err - Error of ratio of the last filter
26) last_ratio - Ratio of the last filter
27) biggest_ratio_err - Error of the biggest ratio
28) biggest_ratio_wv - Wavelength of the filter with the biggest ratio [m]
29) biggest_ratio - Ratio of the filter with the biggest ratio
30) slope_25 - Spectral index 2.2 to 25 micrometers
31) slope_error_25 - St.dev. of spectral index 2.2 to 25 micrometers
32) slope_25_yso_class - Class based on spectral index 2.2 to 25 micrometers
33) slope_20 - Spectral index 2.2 to 20 micrometers
34) slope_error_20 - St.dev. of spectral index 2.2 to 20 micrometers
35) slope_20_yso_class - Class based on spectral index 2.2 to 20 micrometers
36) integrated_excess - Value of integrated IR excess between Rayleigh-Jeans regime and intra-, extrapolation of SED between 4 and 25 micrometers
37) too_high_rayleigh_slope - If too high slope Rayleigh-Jeans slope, usually meaning that something is wrong with the SED
38) points_slope_25 - How many points between 2.2 and 25 um
39) points_slope_20 - How many points between 2.2 and 20 um
40) mir_exists - Whether least 2 points exist beyond 2.2 micrometers
41) good_sed - Stars that have good SEDs
42) sfr_name - Name of star-forming region based on visual location and parallax
43) confidence_sfr - Closer location visually results in higher confidence (0 to 1, 1 indicating being very close to centre, and 0 not being part of any SFR)
44) similar_to_sfr_pm - Whether a star is within 5 sigmas of the SFR's stars' median proper motion (yes, no, ??; ?? - means that no information on SFR's PM is available)
45) main_id_simbad - Name in SIMBAD from 1 arcsec cross-match
46) other_types_simbad - All other types of star in SIMBAD
47) simbad_main_type - Star type in SIMBAD
48) simbad_yso - YSOs identified in SIMBAD (main type)
49) simbad_yso_cand - Only candidates YSO in SIMBAD (main type)
50) simbad_not_yso_or_cand - Not SIMBAD YSO or YSO cand. (main type)
51) ir_excess_criteria - YSO identified by having IR excess (True/False)
52) sfr_criteria - YSO identified by being within SFR and having same PM if applicable (True/False)
53) yso_based_on_either_criteria - YSO identified based on either having IR excess or location within SFR (True/False)
54) yso_based_on_both_criteria - YSO identified by having both IR excess and located within SFR (True/False)
