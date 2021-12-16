* Results of the first stage of simulation, namely run of the Geant4-based code available here: `https://doi.org/10.5281/zenodo.2597039`

* Each folder is for a different source TGF energy spectrum, as described in the paper.
    * MV160: leader 160 MV
    * MV300: leader 300 MV
    * RREA65: epsilon=6.5 MeV
    * RREA: epsilon=7.3 MeV
    * RREA80: epsilon=8.0 MeV
    * RREA100: epsilon=10.0 MeV

* Source TGF altitude is 12 km. Beaming is Gaussian distributed pointing upwards with sigma of 20 degrees.

* Description of the data files :

    * `elec_posi_ratio.txt`: one value indicating the ratio between positrons and electrons

    * `electrons_ener_momentums.txt`: sample list of momentums of electrons along x,y and z direction

    * `positrons_ener_momentums.txt`: sample list of momentums of electrons along x,y and z direction

    * `electrons_spec.txt`: energy spectrum of electrons. First column is the energy grid (values of bin edges) in keV and second column is the spectrum values (dn/de)

    * `positrons_spec.txt`: energy spectrum of positrons. First column is the energy grid (values of bin edges) in keV and second column is the spectrum values (dn/de)