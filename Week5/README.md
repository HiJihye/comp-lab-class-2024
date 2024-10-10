* When I made the T300, T400, and T600, I changed temperature part (ref_t) in each mdp files. (File name: adp_T*.mdp)
T300: ref_t = 300
T400: ref_t = 363
T600: ref_t = 440

* Also, I added below script for trajectory output for XTC file generation
nstxout-compressed = 500
xtc-precision      = 1000
