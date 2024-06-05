The code made in my thesis is listed here. This contains the neutronics and thermal hydraulics for the segmented molten salt reactor. The thesis can be found at https://www.tudelft.nl/tnw/over-faculteit/afdelingen/radiation-science-technology/research/research-groups/reactor-physics-and-nuclear-materials/publications/msc-theses

The code: 'Multiple segments', is the final code

The code: 'Point kinetics + Thermal hydraulics with analysis', is the MSRE benchmarks with an old version of the code

The code: 'Serpent geometry script', contains the code creating the geometry files for Serpent simulations and the fission shape calculations

The file: 'FSOC', is an example of a Serpent file, in this case, the one that runs the FSOC transient. Here the geometry created by the geometry script is included, the salt and graphite are defined with materials and densities, the detectors, pictures and boundary conditions are defined and the amount of cycles and neutrons is defined. 

The file: 'job_FSOC', is an example of how a file is run on the hpc11 cluster.
