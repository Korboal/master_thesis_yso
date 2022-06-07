# master_thesis_yso
Supplementary material for master thesis

**LPV:**

PDFs and output tables are located in the appropriate folders. Three different files for tables exist: they are all the same table just with different file extensions. LPV table includes all 811 analysed files.

**LAV:**

Due to the size of LAV tables and output, they are too big for GitHub. The tables and output PDFs can be accessed at following links. Tables are the same just with different extension. They include all analysed 133717 stars. But, only try to use the stars that were marked as "True" for column "good_sed".

* LAV YSO sample output PDFs in a zip file [7.26 GB] - https://drive.google.com/file/d/1zBmQ-QL6Wuf7PEe1OZUEh4C1Htc44fUn/view?usp=sharing
* LAV YSO sample .fits table [65 MB] - https://drive.google.com/file/d/1oa5M7ReulgbVmSNugxSEkAIdmZVVkdQo/view?usp=sharing
* LAV YSO sample .txt table [159 MB] - https://drive.google.com/file/d/1vr5worX65cJofhFoCYCXR17OVUoYnULi/view?usp=sharing
* LAV YSO sample .html table [135 MB] - https://drive.google.com/file/d/1Xt4h72dAk1C1f328iQQYfXgwVp1BNjjn/view?usp=sharing

**LPV table description**

g2 indicates that the column is taken from Gaia DR2 database.
ge3 indicates that the column is taken from Gaia EDR3 database.

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
