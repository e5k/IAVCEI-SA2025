# Introduction to stable phase equilibrium modelling for magmatic system using MAGEMin

> :fontawesome-solid-users: Nicolas Riel (JGU, Mainz, Germany)
> 
> :fontawesome-solid-calendar-days: Saturday 5th July
> 
> :fontawesome-solid-clock: 08:30-12:30
> 
> :fontawesome-solid-map: [Room M1150](maps_venue.md#__tabbed_3_2)

--- 

MAGEMin is a Gibbs energy minimization solver package, which computes the most stable assemblage for a given bulk rock composition and pressure/temperature condition. It also returns parameters such as melt fraction or density, which can be combined with geodynamic/petrological tools using Julia to simulate, for example, the evolving chemistry of a crystallising melt.

During the workshop participants will first learn how to install and use MAGEMinApp (GUI) to:

1. Generate Pressure-Temperature iso-chemical phase diagrams (PT), and Pressure or Temperature or Pressure-Temperate path versus variable composition phase diagrams (PX, TX, PT-X). Compute trace-elements partitioning and zircon saturation diagrams.
2. Setup initial grid resolution and iteratively increase refinement of the computed diagrams.
3. Change and adjust colormap, add iso-contours and export vector format figures.
4. Export single point information and full diagram information to files (e.g., CSV).
5. Compute Pressure Temperature paths, including fractional melting and crystallization paths.

In a second stage you will learn how to install MAGEMin_C and apply it to targeted stable phase equilibrium computation. Several example of applications will be introduced:

1. Single point and multipoint minimizations using available database.
2. Extraction and visualization of stable phase prediction outputs.
3. Isentropic batch melting path applied to KLB-1 peridotite.


![Footer](img/footer.png){  style="transform: translateY(35px);" }