# Research 

# Plasmonic Colors 

## Understanding color on laser-written metal surfaces
The Royal Canadian Mint together with researchers at UOttawa developed laser ablation and redeposition processes for colouring metallic surfaces without paint. SEM images reveal complex distributions of nanoparticles on the metal surface. Our simulations revealed that colour formation occurs by selective absorption due to plasmonic resonances, and is highly dependent on inter-particle spacing and particle sizes.  This joint experimental-computational work was published in [Nature Communications](https://www.nature.com/articles/ncomms16095) (2017).

<img src = "\img\research\laser-color.jpg" width = "300" height = "200">

## Plasmonic color enhancement via laser-burts
Experiments at the Royal Canadian Mint showed that laser-written colours are more saturated in the presence of an underlying nanostructured topography, such as the ripple structures visible in the SEM image at right. These underlying ripples can have different periodicity along different directions, and they are created via laser bursts. We were able to reproduce and understand the origin of colour saturation as a function of ripple depth via simulation of nanoparticles on a sinusoidal surface. This work is published in [Advanced Optical Materials](https://onlinelibrary.wiley.com/doi/abs/10.1002/adom.201800189) (2018).

<img src = "\img\research\color-enhancement.png" width = "300" height = "300">

## Effect of alumina coating on laser-written colors
In order to passivate the laser-written coloured metal surfaces of the Royal Canadian Mint, atomic layer deposition (ALD) of alumina was investigated. Though only some nanometers thick, the coating was found to change the optical properties of the surfaces, and ultimately the colour. Through detailed simulations we were able to explain the trend seen in experiments, where the colour is observed to change as a function of ALD thickness, and then after a sufficient number of layers, ultimately recovers (see figure below). This work was published in [Nanophotonics](https://www.degruyter.com/view/j/nanoph.ahead-of-print/nanoph-2018-0202/nanoph-2018-0202.xml?format=INT) (2019).

<img src = "\img\research\alumina-coating.png" width = "800" height = "800">

# Metasurfaces and Metamaterials 

## Optical properties of a 3D self-assembled carbon-metal metamaterial
Carbon-based and carbon–metal hybrid materials hold great potential for applications in optics and electronics. Our collaborators fabricated a novel metamaterial consisting of gold–silver nanoparticles intercalated within a crystalline carbon matrix (right), where the carbon atoms are arranged in an orthorhombic lattice. Experiments reveal a high linear birefringence across the visible spectral range. Using a local-field theory applied to the carbon matrix, we linked the birefringence to the orthorhombic unit cell. Through simulations of the metamaterial, we related the observed optical response to the distribution of the alloy nanoparticles and the optical density of the carbon matrix. This work was published in [Small](https://onlinelibrary.wiley.com/doi/abs/10.1002/smll.201900512) (2019).

<img src = "\img\research\carbon-metamaterial.jpg" width = "300" height = "300">

This work was done within the Max Planck–University of Ottawa Centre for Extreme and Quantum Photonics, in collaboration with researchers at the Max Planck Institute for the Science of Light, Germany, and St. Petersburg State University, Russia.

<img src = "\img\logo\mpc_logo.jpg" width = "200" height = "200">

## Creating structured nonlinear light
One of the attractive features of a plasmonic metasurface is the ability to engineer its interaction with light. In this vein, we designed a plasmonic nanoantenna, which we call butterfly, that offers full vectorial control of the light field in its gap. This affords full control of nonlinear optical processes in the gap as well, allowing us to tailor the emitted light beam at will. By placing thousands of such nanoantennas on a surface, we demonstrated the creation of a highly structured optical beam at the third harmonic. It carries a very high degree of orbital angular momentum, important for applications including quantum communications and cryptography. Furthermore, the third harmonic is a frequency not accessible with linear plasmonics. This opens the door to a new paradigm of beam structuring. This was one of the largest simulations of a metasurface at the time – up to 3000 interacting nanoantennas were simulated (see movie below). This work was published in [Optics Express](https://www.osapublishing.org/oe/abstract.cfm?uri=oe-25-3-2569) (2017) as editor’s pick.

# Nonlinear Optical Microscopy 

## Effect of linear index mismatch and near fields
Nonlinear optical microscopes allow for label-free, molecule-specific, non-destructive imaging of biological processes in cells and tissues. Two such techniques are stimulated Raman scattering (SRS) microscopy and coherent anti-Stokes Raman scattering (CARS) microscopy, which allow for video-rate and hyperspectral imaging via molecular Raman resonances.

<img src = "\img\research\index-mismatch.jpg" width = "400" height = "200">

We show in [Optics Express](https://www.osapublishing.org/oe/abstract.cfm?uri=oe-24-22-25752) (2016) that an inhomogeneous linear refractive index profile, such as that occurring in biological tissues, is shown to significantly alter SRS and CARS images. In fact, near-field enhancement and microlensing can increase an object’s perceived molecular density by almost an order of magnitude and can change its perceived position by up to 1.0 μm. Furthermore false CARS and AM-SRS signals can be observed in the absence of Raman active media.

<img src = "\img\research\shg.png" width = "400" height = "200">

Nonlinear optical imaging using backward propagating signals is very sensitive to the location of objects along the laser axis, and thus are used to image very small features. In our [Optics Letters](https://www.osapublishing.org/ol/abstract.cfm?uri=ol-43-20-5082) (2018), we show both theoretically and experimentally that the inhomogeneous refractive index in tendon creates hot or cold spots in the constituent collagen fibrils, which can change the forward to backward signal ratio of the second harmonic generation (SHG) signal by up to 25%. This is caused by the extreme sensitivity of the backward signal on phase matching, which alters the destructive interference condition.

# Computational Nanophotonics

## Convergence and accuracy of FDTD for plasmonics
Though the use of FDTD to model nanoplasmonic structures continues to rise, a comprehensive study on the convergence and accuracy of the method for nanoplasmonic structures had yet to be reported. With access to the largest supercomuter in Canada at the time, the Blue Gene/Q from SOSCIP, we were able to investigate this in detail using our in-house software. Our study in [Optics Express](https://www.osapublishing.org/oe/abstract.cfm?uri=oe-23-8-10481) (2015), not only provides a thorough test of accuracy, convergence and high performance computing scalability, but presents useful guidelines for FDTD simulations for the plasmonic community, including highlighting where FDTD simulations fail.

We simulated three nanoplasmonic structures with unprecedented resolution:

# Artificial Intelligence for Nanophotonics

## Direct Prediction
We use deep learning to predict colours from nano-structured surfaces. Using data acquired in the Plasmonic Colours work, we trained Deep Neural Networks to predict the colours that result from different laser settings or different nanoparticle geometries. This allows us to accurately predict the outcome of an experiment or simulation without having to run the experiment or the time-consuming simulation, saving both time and money. 

<img src = "\img\research\direct-prediction.png" width = "500" height = "200">

## Inverse Design
We’ve developed a new method for inverse design using deep learning. Given a colour, this method iteratively seeks to find what nanoparticle geometry or laser settings will give this colour. The method is straight forward to implement and effective. 

This work has been published in [Nature Scientific Reports](https://www.nature.com/articles/s41598-019-44522-7)

<img src = "\img\research\inverse-design.png" width = "500" height = "200">