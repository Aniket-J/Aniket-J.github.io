---
title: Professional stuff
feature_image: "https://picsum.photos/2560/600?image=232"
aside: false
---
# What I bring to the table

I have a broad skillset that I have enhanced over the years. My current focus is on data-driven solutions for complex systems. I'm especially interested in roles that aim to combine machine learning with rigorous scientific avenues. Even better if it involves a bit of Material Science!

My diverse set of experiences would make me a valuable addition to any team, and I would prove to be an asset with my quick learning abilities. I have also led collaborative multinational studies and worked on a breadth of physical computation domains. 

Please feel free to reach out if you have any queries! My details are in the [Contact](../contact/) tab.
# Experience

##### PhD Researcher, The Open University **(October 2019 - Current)** #####
My PhD deals with high-temperature performance of materials and how they perform at a small-scale.

Broadly, this can be divided into 3 phases:

* Experimentation
* Simulation
* Machine learning

The experiments involved are a departure from the conventionally used big specimens in the industry. My research adopts miniaturized novel specimen geometries for these tests. Volumetrically, my newly designed test technique provides a materials saving of 97.89%.

My research would make it easier to inspect powerplants and jet-engines with minimal amount of material, therefore not impacting the structural integrity. This would help in the development of new alloys and test irradiated structures with a higher safety margin.

I've gone one step further in my research and I'm investigating the feasibility of combining 3 tests from a single specimen (Small Punch + Small Ring Test). Volumetrically this would result in an 85x smaller specimen overall. Combing 3 tests (creep, tensile, fatigue) is also groundbreaking for these industries. My research overview is outlined below.

{% include figure.html image="/assets/images/Website_professional_thesis.svg" caption="Research plan outline." width="800" height="1000" %}

This combination can be visualized in the image below, with the ring painted for computer-vision based strain imaging. 

{% include figure.html image="/assets/images/Professional_ring_disc_combination.jpg" caption="Visualizing my hypothesis of combining ring and disc testing." width="800" height="1000" %}

I have used optimization routines in conjunction with numerical simulations to obtain unknown material parameters. I leveraged this technique to translate the test's force-displacement data to a more general-purpose stress-strain data for this new testing methodology.

This data was then fed into regression models (XGBoost and Random Forests, primarily) to analyse rate-dependency of the test. The models trained well with an R2 score of 0.95632 and the predictions were extremely close on new hidden data as well, as seen in the image below.

{% include figure.html image="/assets/images/316L_RT_SRTT_0_3333mmMin_cleaned_RFRandXGB_limited.png" caption="Predictions on new experiments." width="800" height="1000" %}


Extensive data cleaning procedures were also analysed, such as butterworth signal filtering (shown below) or the convolution smoothing.

{% include figure.html image="/assets/images/butterworth_filter_example.png" caption="Cleaning up the test data." width="800" height="1000" %}

Using the power of physics baked in with my analytical solution, I devised a physics-informed data-driven conversion method that allows users to obtain material parameteres directly without the need of any expensive simulations.

Below are a couple of images of the Small Ring Test as well. Images are taken from a Nikon D850 camera. 

{% include figure.html image="/assets/images/SRT_initial.jpg" caption="Small Ring Test- Ring specimen (SS316L) at the start of test." width="800" height="1000" %}

{% include figure.html image="/assets/images/SRT_final.jpg" caption="Small Ring Test- Ring specimen (SS316L) at the end of test." width="800" height="1000" %}

In addition to this, I am also responsible for maintaining the department's proprietary software (written in MATLAB) for Digital Image Correlation

##### Research Assistant, Imperial College London (NTP - PROTECT) **(April 2021 - March 2022)** #####

As part of the National Transmission Project (NTP), PROTECT portfolio, I worked as a Research Assistant within the AMCG (Applied Modelling & Computation Group) at Imperial College London. 

My work involved analyzing the propagation of air-flows in different built environments. My work went on to inform the knowledge domain for COVID-19 and how mitigating measures may be implemented for better health and safety of occupants in any given structure. 

This work involves numerical simulations on [IC-FERST](https://multifluids.github.io/) for large-scale geometries/structures that are also designed with the help of an in-house software.

Unfortunately, due to the confidential nature of this work, I am not able share any cool images relating to this. 

##### Visiting Researcher, Imperial College London **(October 2019 - September 2022)** #####

This role pertained largely to research in severe accidents in nuclear reactors, and was a part of an ongoing effort to establish international cooperation between AMCG and other academic partners. We published a hugely collaborative paper (titled ['Numerical Study of the Effect of Geometry on the Behaviour of Internally Heated Melt Pools for In-Vessel Melt Retention'](https://doi.org/10.1016/j.pnucene.2022.104555)).

In this role, I supervised MSc projects with our partners and enhance IC-FERST's capabilities (in-house numerical simulation software) for better simulating severe accidents.

The severe accidents pertain to a cataclysmic event in the lower-head of a reactor pressure vessel, where all the fuel material collects post-accident. More specifically, this work involves simulating the cooling of this fuel debris (it emits a lot of residual heat) and analyze its safety. Below is a snapshot of the fluid dynamics in this reactor after 8 seconds of simulation. 

{% include figure.html image="/assets/images/tstep8_temp_velvec_nomesh.png" caption="Velocity vectors superimposed on the temperature field background. Simulation of lower-head of a reactor pressure vessel." width="800" height="1000" %}


##### Project Intern, DRDO, India **(Dec 2017 - May 2018)** #####

This role involved performing a lot of finite element analysis (FEA), especially in the domain of shock physics and shock loading. Coming into this role, I had virtually zero knowledge about these domains.

However, I was soon simulating shock physics and structural interactions for the design of shock-resistant structures in my role. 

I was also leading a study that analysed the effect of variation of geometry in cylindrical charges. This was in addition to other numerous activities, such as analyzing foam attenuation and soil attenuation, that I contributed to.

My role was brief but extremely intensive and I successfully delivered on numerous projects. 

References available upon request.
# Education

##### PhD: The Open University (2019 - current) #####

* Research area: Materials Science and Machine Learning.
* Thesis: Evaluation and optimisation of the Small Ring Test and its amalgamation with the Small Punch Test.

##### MSc: Imperial College London, Advanced Nuclear Engineering (Distinction) #####
* Thesis: Numerical Modelling of In-Vessel Melt Retention: The LIVE Experiments.
* Awarded the William Penney Prize for my thesis work.

##### BTech: VIT University, Mechanical Engineering (9.1/10) #####
* Thesis: Analysis of shockwave propagation in air.

# Select Publications

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Physics and data driven approach to analysing the Small Ring Tensile Test on SS316L at multiple displacement rates.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Leveraging digital image correlation for the design of a new strain measurement system for the Small Ring Tensile Test.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Preliminary results on feasibility of combination of the Small Ring Test and the Small Punch Test.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Open Source Digital Image Correlation Analysis Data on Select Open Source Data for Small Ring Tensile Test.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **"Open-Source Data for Small Ring Tensile Test performed on SS316L at multiple displacement rates."** *Open Research Data Online, The Open University.*

Akash Venkateshwaran, Mahendhar Kumar, Shyam Kumar, R. Sivakumar, **Aniket Joshi**, and Christopher Pain. **"Numerical study of the effect of geometry on the behaviour of internally heated melt pools for in-vessel melt retention."** *Progress in Nuclear Energy 156* (2023): 104555.

**Aniket Joshi**, Alex Forsey, Richard Moat, and Salih Güngör. **"Preliminary results on conducting Small-Ring Test and Small-Punch Test on the same specimen."** *Transactions, SMiRT-26, 2022.*

Rossella Arcucci, César Quilodrán Casas, **Aniket Joshi**, Laetitia Mottet, Asiri Obeysekara, Yi-Ke Guo, and Christopher Pain. 
**"Enhancing CFD simulations of COVID-19 diffusion by coughing and sneezing using data assimilation."** *High Performance Computing on CRESCO Infrastructure: research activity and results 2020 (2021): 52.*

**Aniket Joshi**, Claire Heaney, Alan Jones, Liang Yang, Paul Smith, Ali Tehrani, Christopher C Pain. **"Numerical modelling of in-vessel melt retention: The LIVE Experiments."** *25th International QUENCH Workshop: 22-24 October 2019, Karlsruhe Institute of Technology, Karlsruhe, Germany.*
