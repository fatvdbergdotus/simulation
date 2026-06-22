# A Simpy implementation of Chapter 4 of my PhD thesis
See [Jupyter Notebook](phd_thesis/09%20PhD%20thesis%20iDSL.ipynb)

See also [https://drops.dagstuhl.de/entities/document/10.4230/OASIcs.MCPS.2014.80](https://drops.dagstuhl.de/entities/document/10.4230/OASIcs.MCPS.2014.80) also for the published paper and [https://github.com/fatvdbergdotus/diploms-and-grades/blob/main/publications/thesis_F_van_den_Berg.pdf](https://github.com/fatvdbergdotus/diploms-and-grades/blob/main/publications/thesis_F_van_den_Berg.pdf) for the whole PhD thesis of which Chapter 4 is focal.

A SimPy simulation of a Philips Imaging System with two concurrent systems, the so-called Biplane system, for 3D images. The so-called Philips iXR (Interventional X-Ray) systems are advanced image-guided therapy platforms designed to support minimally invasive cardiovascular, vascular, neurological, and oncological procedures. By combining high-quality real-time X-ray imaging with sophisticated visualization, navigation, and workflow technologies, these systems help clinicians diagnose and treat patients with greater precision while reducing procedure complexity. Philips iXR solutions, including the Allura and Azurion product families, are designed to improve clinical outcomes, enhance workflow efficiency, and support lower radiation dose levels without compromising image quality, making them a key component of modern interventional healthcare environments.

Both systems need to repeat for shared resources and what can be seen from different simulation runs is that when the different imaging systems are further apart in time, less concurrency happens.

A CDF for different times is the result (as embedded in the Jupyter Notebook).
