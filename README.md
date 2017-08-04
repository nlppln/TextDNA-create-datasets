# Create datasets for TextDNA

Docker container to create datasets that can be visualized using [TextDNA](http://graphics.cs.wisc.edu/Vis/SequenceSurveyor/TextDNA.html).

## Usage

This Docker container was made to be used in [nlppln](https://github.com/WhatWorksWhenForWhom/nlppln).

The CWL command line tool for TextDNA data generation is `textDNA-generate.cwl`.

More information about TextDNA can be found on [their website](http://graphics.cs.wisc.edu/Vis/SequenceSurveyor/TextDNA.html) and in the [github repository](https://github.com/uwgraphics/Release-TextDNA).

## Credit

Credit for TextDNA belongs to Danielle Albers Szafir ([danielle.szafir@colorado.edu](mailto:danielle.szafir@colorado.edu)), who originally developed the program and website documentation under the guidance of Michael Gleicher and Robin Valenza. The TextDNA user interface was further developed by Yusef Sohail under the direction of Szafir. The two fine-tuned the system for raw text in consultation with Deidre Stuffer, who provided documentation for raw text manipulation and generated the test dataset with documentation to help users learn TextDNA functions. Erin Winter provided scripts to generate csv datasets from plaintext input for the public release. The Docker container for data generation was made by [Janneke van der Zwaan](https://www.esciencecenter.nl/profile/dr.-janneke-van-der-zwaan).

If you use the TextDNA software, please cite:
> D.A. Szafir, D. Stuffer, Y. Sohail, & M. Gleicher. “TextDNA: Visualizing Word Usage Patterns with Configurable Colorfields.” *Computer Graphics Forum.* 35 (3), 2016. (In the Proceedings of the 2016 Eurographics/IEEE Conference on Visualization) [PDF](http://graphics.cs.wisc.edu/Papers/2016/ASSG16/TextDNA.pdf)
