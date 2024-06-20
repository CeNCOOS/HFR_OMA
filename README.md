This is a repository of code from the old cencalcurrents.org site.<p>
The site used to use OMA on a nearly closed boundary to compute totals within a region.  This was to create a more complete grid.
This grid of data could then be used for multiple purposes.  The original code was written in matlab.  The boundary solution harmonics 
only had to be computed once but depened upon the partial differential equation solver of matlab. This solver was in a toolbox that was 
not part of the base matlab distribution.  The solver is only used to get the modes and the other OMA code can be run without the solver after the modes have been computed.
