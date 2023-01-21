# Conjugated-Dyes
A simulation of uv-vis absorption spectra of a handful of cyanine dyes

This program is designed to complement a common experiment in undergraduate physical chemistry teaching laboratories in which students apply the particle-in-a-box model (PIB) to predict the HOMO-LUMO transition energy of cyanine dyes with different polymethine chain lengths.

As a brief overview, the π-electrons in the polymethine chain occupy the HOMO (highest occupied molecular orbital) and are therefore responsible for the color of the dye. These electrons experience little potential energy within the chain, but are restricted (to an extent) from entering the end groups. This system can be modeled using the PIB.

Predictions using this model follow the correct trend (energy and chain length are inversely related), but deviate from measured values by several eV. Predicted values can be brought in line with measurement by introducing a "correction factor" to the length of the chain. This correction factor is found experimentally, and students are often tasked with giving a physical explanation for the correction factor and possibly with proposing a follow up experiment to test this hypothesis. However, it can be difficult to provide students with the opportunity to perform this follow experiment due to limitations in time and materials.

This program aims to provide an opportunity for students to collect absorption spectra from additional conjugated dyes. The program has approximately 40 dyes available, the spectra of which can be collected by selecting (1) the dye, (2) the volume of a 1E-3 M stock solution of the dye and (3) the volume of the solvent (MeOH). Each spectrum is simulated using the sum of 4 gaussians, the parameters of which are chosen to fit spectra which are collected either in-house or gathered from published sources.

To use this program, download the zip folder and unzip in the desired location. The executable, .exe, can then be run from the unzipped folder.

Once running, the desired dye and concentration can be selected using the appropriate drop-down menu and entry cells. The progrom will display a simulated spectra modeled using four gaussian functions the parameters of which were determined by fitting to spectra either collected from the chemistry labs at the University of Florida in Gainesville or found in the literature. The concentration should be kept low (determined by the molar absorptivity and concentration) so that the absorption is below 1.

Currently there is only a windows version of the program.
