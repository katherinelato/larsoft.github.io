LArSoft v06\_26\_01\_11 Release Notes
=============================================================================

-   **Table of contents**
-   [LArSoft v06\_26\_01\_11 Release Notes](#LArSoft-v06_26_01_11-Release-Notes)
    -   [Purpose](#Purpose)
    -   [New features](#New-features)
    -   [Bug fixes](#Bug-fixes)
    -   [Updated dependencies](#Updated-dependencies)
-   [Change List](#Change-List)
    -   [larsoft v06\_26\_01\_11](#larsoft-v06_26_01_11)
    -   [lareventdisplay v06\_02\_14\_11](#lareventdisplay-v06_02_14_11)
    -   [larexamples v06\_01\_15\_07](#larexamples-v06_01_15_07)
    -   [larpandora v06\_08\_00\_11](#larpandora-v06_08_00_11)
    -   [larwirecell v06\_00\_13\_09](#larwirecell-v06_00_13_09)
    -   [larana v06\_03\_18\_11](#larana-v06_03_18_11)
    -   [larreco v06\_20\_00\_11](#larreco-v06_20_00_11)
    -   [larsim v06\_13\_01\_07](#larsim-v06_13_01_07)
    -   [larevt v06\_07\_09\_07](#larevt-v06_07_09_07)
    -   [lardata v06\_14\_04\_06](#lardata-v06_14_04_06)
    -   [larcore v06\_05\_03\_03](#larcore-v06_05_03_03)
    -   [larpandoracontent v03\_07\_02\_05](#larpandoracontent-v03_07_02_05)
    -   [larsoftobj v1\_11\_00\_06](#larsoftobj-v1_11_00_06)
    -   [lardataobj v1\_11\_00\_06](#lardataobj-v1_11_00_06)
    -   [larcoreobj v1\_06\_02\_03](#larcoreobj-v1_06_02_03)

[list of LArSoft releases](LArSoft_release_list)
Download instructions for [larsoft v06\_26\_01\_11](http://scisoft.fnal.gov/scisoft/bundles/larsoft/v06_26_01_11/larsoft-v06_26_01_11.html)
Download instructions for [just larsoftobj v1\_11\_00\_06](http://scisoft.fnal.gov/scisoft/bundles/larsoftobj/v1_11_00_06/larsoftobj-v1_11_00_06.html)

Purpose
--------------------

-   for MicroBooNE mcc8 production
-   [\#19561](/redmine/issues/19561 "Support: Request patch release larsoft v06_26_01_11 (Closed)")

New features
------------------------------

Bug fixes
------------------------

Updated dependencies
----------------------------------------------

Change List
============================

larsoft v06\_26\_01\_11
-------------------------------------------------

-   2018-04-04 Lynn Garren : modernize
-   2018-04-04 Lynn Garren : mrb
-   2018-04-04 Lynn Garren : update versions
-   2018-04-04 Lynn Garren : larsoft v06\_26\_01\_11 for larsoft v06\_26\_01\_01\_branch

lareventdisplay v06\_02\_14\_11
-----------------------------------------------------------------

-   2018-04-04 Lynn Garren : lareventdisplay v06\_02\_14\_11 for larsoft v06\_26\_01\_01\_branch

larexamples v06\_01\_15\_07
---------------------------------------------------------

-   2018-04-04 Lynn Garren : larexamples v06\_01\_15\_07 for larsoft v06\_26\_01\_01\_branch

larpandora v06\_08\_00\_11
-------------------------------------------------------

-   2018-04-04 Lynn Garren : larpandora v06\_08\_00\_11 for larsoft v06\_26\_01\_01\_branch

larwirecell v06\_00\_13\_09
---------------------------------------------------------

-   2018-04-04 Lynn Garren : larwirecell v06\_00\_13\_09 for larsoft v06\_26\_01\_01\_branch

larana v06\_03\_18\_11
-----------------------------------------------

-   2018-04-04 Lynn Garren : larana v06\_03\_18\_11 for larsoft v06\_26\_01\_01\_branch
-   2018-02-10 David Caratelli : updates to algorithms –David Caratelli
-   2018-02-08 David Caratelli : adding TruncatedMean functionality. First skeleton is there, to be expanded –DC

larreco v06\_20\_00\_11
-------------------------------------------------

-   2018-04-04 Lynn Garren : larreco v06\_20\_00\_11 for larsoft v06\_26\_01\_01\_branch

larsim v06\_13\_01\_07
-----------------------------------------------

-   2018-04-04 Lynn Garren : larsim v06\_13\_01\_07 for larsoft v06\_26\_01\_01\_branch
-   2018-04-04 Wesley Ketchum : add in the flags for MCC80Compat mode
-   2018-03-15 Wesley Ketchum : Merge branch ‘feature/wketchum\_LArG4Edeps\_2’ of ssh://cdcvs.fnal.gov/cvs/projects/larsim into feature/wketchum\_LArG4Edeps\_2
-   2018-03-15 Wesley Ketchum : switch to using service to get recombA parameter?
-   2018-03-14 Wesley Ketchum : remove the sim energy deposits from larvoxel since we do not use them there for the moment
-   2018-03-14 Wesley Ketchum : updates to the propagation modules, cleanup
-   2018-03-14 Wesley Ketchum : refactor the refactoring to clean it up
-   2018-03-13 Wesley Ketchum : updates to get the photon library propagation module working
-   2018-03-03 Wesley Ketchum : make energy depositions from opfastscintillation physics
-   2018-02-26 Wesley Ketchum : add in the simdriftelectron module from Bill, and some updates
-   2018-02-19 Wesley Ketchum : fix clearing of edeps before one should, and reduce reserve size on photon library
-   2018-02-19 Wesley Ketchum : backout of the slightly improved but not really given implementation SCE calculations
-   2018-02-18 Wesley Ketchum : add in module for doing standalone photon propagation based on photon library and edeps
-   2018-02-18 Wesley Ketchum : add ElectronDrift code
-   2018-02-18 Wesley Ketchum : add an IonizationScintillation directory that is separate from LArG4, to be used for separated LArG4
-   2018-02-18 Wesley Ketchum : fix for initial sim energy deposit and now working though i saw an event with no edeps??
-   2018-02-18 Wesley Ketchum : add energy deposition storage to LArG4 module
-   2018-02-18 Wesley Ketchum : add in energy deposition creation options in LArVoxelReadout

larevt v06\_07\_09\_07
-----------------------------------------------

-   2018-04-04 Lynn Garren : larevt v06\_07\_09\_07 for larsoft v06\_26\_01\_01\_branch

lardata v06\_14\_04\_06
-------------------------------------------------

-   2018-04-04 Lynn Garren : lardata v06\_14\_04\_06 for larsoft v06\_26\_01\_01\_branch

larcore v06\_05\_03\_03
-------------------------------------------------

-   2018-04-04 Lynn Garren : larcore v06\_05\_03\_03 for larsoft v06\_26\_01\_01\_branch

larpandoracontent v03\_07\_02\_05
---------------------------------------------------------------------

larsoftobj v1\_11\_00\_06
-----------------------------------------------------

-   2018-04-04 Lynn Garren : larsoftobj v1\_11\_00\_06 for larsoft v06\_26\_01\_01\_branch

lardataobj v1\_11\_00\_06
-----------------------------------------------------

-   2018-04-04 Lynn Garren : lardataobj v1\_11\_00\_06 for larsoft v06\_26\_01\_01\_branch
-   2018-03-14 Wesley Ketchum : compare function has problems
-   2018-02-19 Wesley Ketchum : class def update
-   2018-02-18 Wesley Ketchum : add pdg code to SimEnergyDeposit
-   2018-02-18 Wesley Ketchum : add in the SimEnergyDeposit class from later commits

larcoreobj v1\_06\_02\_03
-----------------------------------------------------

-   2018-04-04 Lynn Garren : larcoreobj v1\_06\_02\_03 for larsoft v06\_26\_01\_01\_branch
-   2018-02-12 Gianluca Petrillo : Removed unnecessary header.
-   2018-02-12 Gianluca Petrillo : Standardised include guard for sumdata::RunData header
-   2018-02-12 Gianluca Petrillo : Pass string by reference in sumdata::RunData methods
-   2018-02-12 Gianluca Petrillo : Documentation changes to sumdata::RunData
-   2018-02-12 Gianluca Petrillo : Added sumdata::RunData::aggregate() method.