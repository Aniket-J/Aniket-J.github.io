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

##### ML Research Engineer, Imperial College London **(Oct 2024 - Mar 2025)** #####

This has been one of the most ambitious and rewarding role that I've had. AMCG (Applied Modelling and Computation Group) needed something that consolidated all of it's burgeoning Gen AI tech stack under a single umbrella. AI4PDEs is one of their arms that is a Foundational AI model, but there was no Foundational Generative AI model. This is where I come in. 

I developed RAPIDS (Rapid AI-Powered Image-to-Dynamic Simulations) for AMCG, which will serve as the group's workhorse for years to come. RAPIDS is a grid and size invariant architecture that offers tons of flexbility in what kind of model to train. The image below showcases a few of the major permutations of the Foundational Gen AI models that can be trained with RAPIDS. It is also extremely extensible and modular and flexible in its approach.

{% include figure.html image="/assets/images/RAPIDS_config_basic.png" caption="RAPIDS major configs" width="800" height="1000" %}

The flexibility allows for RAPIDS to be trained on anything and infer on something else entirely. For instance, a model from RAPIDS can be trained on a flow past car case, and then can be used to infer on a flow past building case. Same goes for porous media and carbon sequestration. Some demo videos below.

<div style="text-align: center;">
  <video width="1000" height="800" controls>
    <source src="/assets/videos/unetpp.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-style: italic;">Flow past car. Left is ground truth, middle is UNet++ (implicit) from RAPIDS, and the right side is the difference field.</p>
</div>

<div style="text-align: center;">
  <video width="1000" height="800" controls>
    <source src="/assets/videos/co2capture.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-style: italic;">Carbon sequestration in RAPIDS showing the various fields. Left is ground truth, middle is a UNet++ (explicit) from RAPIDS, and the right side is the difference field.</p>
</div>

I am super excited to see how RAPIDS changes the world and how AMCG uses it. We have around 6 publications upcoming for this, including a few in NeurIPS to demonstrate some of the cool new Gen AI stuff we developed, including some that I came up with originally as well! To summarise, few things that I have been responsible for and delivered on:

* Secured partnership for AMCG worth £6m (more in progress).
* Lead Dev for RAPIDS, next gen Foundational Generative AI software.
    * With CI/CD pipelines.
    * Developed new tech within RAPIDS.
    * Folded in existing tech of AMCG within RAPIDS.
    * Made sure the package is highly extensible, modular, and test-driven.
    * Dockerised all architectures for industrial partners, ensuring consistent and scalable Gen AI.
* Wrote AI-PULSE (Artistic Intelligence for Personal Understanding of Language, Systems, and Experiences) grant (£1.2m), that was selected internally by both Royal College of Arts and Imperial College London for UKRI Cross Research Council Call.
    * Invited to final stage.
* Co-lead dev for SCAlED, a subset of RAPIDS that uses Diffusion Gen AI.
* Developed novel in-painting techniques to enhance long-term Gen AI video stability.
* Pioneered PDE-based adaptive training for improved stability in long-term image/video predictions.
* Led research to incorporate complex physical constraints into Gen AI models.

##### Creative Technologist, Young Vic Theatre **(Feb 2025 - Mar 2025)** #####

In this role I took over the tech stack of Young Vic Theatre that relates to the deployment of artistic interventions via Meta communication channels. We chose to go with WhatsApp due to its prevalence.

This role allowed me to unleash my skills in arts and engineering as I combined them to develop a tech platform that is future-proof for the Theatre, allowing for artists to deploy their interventions seamlessly during a live play.

This was eventually deployed for a hugely successful run of Five Shorts.

##### Gen AI Research Engineer, Royal College of Art & Young Vic Theatre **(Mar 2024 - Jul 2024)** #####

As seems to be the case with everything now, this role covered a lot of things (and I say this positively), and has been super fun. Few things that I have been responsible for and delivered on:

* Deployed Agentic LLM systems in prod in context of a theatrical setting.
* Synthesized speech Gen AI and explored the effect of Image Gen AI in the space of performing arts.
* Evaluated feasibility of different LLMs, spanning proprietary (OpenAI, Gemini, etc) and open-source (Llama 2 + 3, Mistral, etc) models.
* Customised LLMs above using client data after identifying appropriate strategy (LoRA, ORPO, etc).
* Designed and deployed LLM tech stack in AWS Sagemaker (monitored via Shadow inferencing and Cloudwatch).
* Developed in-house software for organisation to extract data from own docs for precise LLM fine-tuning.
* Co-authored extensive multinational collaborative grants (£5m+) to address ethics in Gen AI.

This role has given me a deep insight into something I deeply care about: LLM deployment but responsibly. Ethics in Gen AI are a tricky issue and navigating this in a production environment has been extremely rewarding and it's a super awesome system!

##### MLOps Engineer, Point Zero Solutions **(Dec 2022 - Feb 2024)** #####

This role covers a lot of things. Mainly, these are the few things that I have been responsible for and delivered on:

* Build up the tech stack
* Build APIs for GCP and mobile app integration
* Build MLOps pipelines
* Maintain all of the above
* Secured GCP start-up award ($350k)

All things considered, this has been a challenging and rewarding experience.

The initial challenge was to connect to the client sites and transfer data to the Pzeros database. To resolve this, I wrote some scripts on the devices that are sent out to the clients (with everything pre-installed), and the device starts uploading the images to our database as soon as it's linked up.

Once this is done, the real analysis begins. Vertex AI is great for deployment, but it's not very nice for ONNX deployments. To resolve this, I containerize the models and use the Artifact Registry (after Cloud Build fetches from GitHub) to feed into GCP as an Vetex AI endpoint.

This inference, which is obtained once any new image is uploaded, is written to BigQuery, which in turns feeds into the Looker Dashboards for the client whose images are under consideration.

This forms the core service of the firm, which you can read about more on the firm's [website](https://pzeros.com/). 

##### PhD Researcher, The Open University **(Oct 2019 - Sep 2023)** #####
My PhD deals with high-temperature performance of materials and how they perform at a small-scale.

Broadly, this can be divided into 3 phases:

* Experimentation
* Simulation
* Machine learning

The experiments involved were a departure from the conventionally used big specimens in the industry. My research adopts miniaturized novel specimen geometries for these tests. Volumetrically, my newly designed test technique provides a materials saving of 97.89%.

My research would make it easier to inspect powerplants and jet-engines with minimal amount of material, therefore not impacting the structural integrity. This would help in the development of new alloys and test irradiated structures with a higher safety margin.

I've gone one step further in my research and I'm investigating the feasibility of combining 3 tests from a single specimen (Small Punch + Small Ring Test). Volumetrically, this resulted in materials savings of 97.89%. Combing 3 tests (creep, tensile, fatigue) is also groundbreaking for these industries. My research overview is outlined below.

{% include figure.html image="/assets/images/Website_professional_thesis.svg" caption="Research outline." width="800" height="1000" %}

This combination can be visualized in the image below, with the ring painted for computer-vision based strain imaging. 

{% include figure.html image="/assets/images/Professional_ring_disc_combination.jpg" caption="Visualizing my hypothesis of combining ring and disc testing." width="800" height="1000" %}

I used optimization routines in conjunction with numerical simulations to obtain unknown material parameters. I leveraged this technique to translate the test's force-displacement data to a more general-purpose stress-strain data for this new testing methodology.

This data was then fed into regression models (XGBoost and Random Forests, primarily) to analyse rate-dependency of the test. The models trained well with an R2 score of 0.95632 and the predictions were extremely close on new hidden data as well, as seen in the image below. 

{% include figure.html image="/assets/images/316L_RT_SRTT_0_3333mmMin_cleaned_RFRandXGB_limited.png" caption="Predictions on new experiments via RFR and XGBoost." width="800" height="1000" %}

My original experiments also performed largely well, as you can see in the heatmaps below. For the Small Ring Test (SRT) I performed 48 experiments at different pin displacement rates and for the Small Punch Test (SPT) I analysed the discs separately and both sets of inter-test comparison results are shown below:

{% include figure.html image="/assets/images/SRTT_heatmap_R2scoreMinMax.png" caption="Inter-test comparison R2-scores for all the SRT experiments, with each tick representing the pin displacement rate in mm/min." width="800" height="1000" %}

{% include figure.html image="/assets/images/SPTT_heatmap_R2ScoreMinMax.png" caption="Inter-test comparison R2-scores for all the SPT experiments, with each tick representing the pin displacement rate in mm/min in the brackets. The `B` prefix represents the hypothesis batch (5 batches were tested) and the disc number represented by `D`. The `Norm` represents the normally extracted discs." width="800" height="1000" %}

Extensive data cleaning procedures were also analysed, such as butterworth signal filtering (shown below) or the convolution smoothing. See the image below! I also devised a data-cleaning GUI-app for the department so that people don't have to go through the faff of creating this from scratch for their experiments. [GitHub repo here.](https://github.com/Aniket-J/MatSci-DC/tree/main)

{% include figure.html image="/assets/images/butterworth_filter_example.png" caption="Visualising the cleaning up the test input data with Butterworth filter." width="800" height="1000" %}

Using the power of physics baked in with my analytical solution, I devised a physics-informed data-driven conversion method that allows users to obtain material parameteres directly without the need of any expensive simulations for the Small Ring Test.

Below are a couple of images of the Small Ring Test as well. Images are taken from a Nikon D850 camera. 

{% include figure.html image="/assets/images/SRT_initial.jpg" caption="Small Ring Test- Ring specimen (SS316L) at the start of test." width="800" height="1000" %}

{% include figure.html image="/assets/images/SRT_final.jpg" caption="Small Ring Test- Ring specimen (SS316L) at the end of test." width="800" height="1000" %}

##### Research Assistant, Imperial College London (NCS - PROTECT) **(Apr 2021 - Mar 2022)** #####

As part of the National Transmission Project (NTP), PROTECT portfolio, I worked as a Research Assistant within the AMCG (Applied Modelling & Computation Group) at Imperial College London. 

My work involved analyzing the propagation of air-flows in different built environments. My work went on to inform the knowledge domain for COVID-19 and how mitigating measures may be implemented for better health and safety of occupants in any given structure. 

This work involves numerical simulations on [IC-FERST](https://multifluids.github.io/) for large-scale geometries/structures that are also designed with the help of an in-house software.

Unfortunately, due to the confidential nature of this work, I am not able share any cool images relating to this. 

##### Visiting Researcher, Imperial College London **(Oct 2019 - Sep 2022)** #####

This role pertained largely to research in severe accidents in nuclear reactors, and was a part of an ongoing effort to establish international cooperation between AMCG and other academic partners. We published a hugely collaborative paper (titled ['Numerical Study of the Effect of Geometry on the Behaviour of Internally Heated Melt Pools for In-Vessel Melt Retention'](https://doi.org/10.1016/j.pnucene.2022.104555)).

In this role, I supervised MSc projects with our partners and enhance IC-FERST's capabilities (in-house numerical simulation software) for better simulating severe accidents.

The severe accidents pertain to a cataclysmic event in the lower-head of a reactor pressure vessel, where all the fuel material collects post-accident. More specifically, this work involves simulating the cooling of this fuel debris (it emits a lot of residual heat) and analyze its safety. Below is a snapshot of the fluid dynamics in this reactor after 8 seconds of simulation. 

{% include figure.html image="/assets/images/tstep8_temp_velvec_nomesh.png" caption="Velocity vectors superimposed on the temperature field background. Simulation of lower-head of a reactor pressure vessel." width="800" height="1000" %}

# Education

##### PhD: The Open University #####

* Research area: Materials Science and Machine Learning.
* Thesis: Evaluation and optimisation of the Small Ring Test and its amalgamation with the Small Punch Test.

##### Masters: Imperial College London, Advanced Nuclear Engineering (Distinction) #####
* Thesis: Numerical Modelling of In-Vessel Melt Retention: The LIVE Experiments.
* Awarded the William Penney Prize for my thesis work.

##### Bachelors: VIT University, Mechanical Engineering (9.1/10) #####
* Thesis: Analysis of shockwave propagation in air.

# Select Publications

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Physics and data driven approach to analysing the Small Ring Tensile Test on SS316L at multiple displacement rates.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Leveraging digital image correlation for the design of a new strain measurement system for the Small Ring Tensile Test.** *Under Review (w/ Experimental Mechanics).*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Preliminary results on feasibility of combination of the Small Ring Test and the Small Punch Test.** *Under Review.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **Open Source Digital Image Correlation Analysis Data on Select Open Source Data for Small Ring Tensile Test.** *Open Research Data Online, The Open University.*

**Aniket Joshi**, Alex Forsey, Richard Moat, Salih Güngör. **"Open-Source Data for Small Ring Tensile Test performed on SS316L at multiple displacement rates."** *Open Research Data Online, The Open University.*

Akash Venkateshwaran, Mahendhar Kumar, Shyam Kumar, R. Sivakumar, **Aniket Joshi**, and Christopher Pain. **"Numerical study of the effect of geometry on the behaviour of internally heated melt pools for in-vessel melt retention."** *Progress in Nuclear Energy 156* (2023): 104555.

**Aniket Joshi**, Alex Forsey, Richard Moat, and Salih Güngör. **"Preliminary results on conducting Small-Ring Test and Small-Punch Test on the same specimen."** *Transactions, SMiRT-26, 2022.*

Rossella Arcucci, César Quilodrán Casas, **Aniket Joshi**, Laetitia Mottet, Asiri Obeysekara, Yi-Ke Guo, and Christopher Pain. 
**"Enhancing CFD simulations of COVID-19 diffusion by coughing and sneezing using data assimilation."** *High Performance Computing on CRESCO Infrastructure: research activity and results 2020 (2021): 52.*

**Aniket Joshi**, Claire Heaney, Alan Jones, Liang Yang, Paul Smith, Ali Tehrani, Christopher C Pain. **"Numerical modelling of in-vessel melt retention: The LIVE Experiments."** *25th International QUENCH Workshop: 22-24 October 2019, Karlsruhe Institute of Technology, Karlsruhe, Germany.*
