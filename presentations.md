---
title: 
feature_text: |
     
feature_image: "../assets/banner/banner_github.jpg"
aside: true
---
<style>
    .presentation {
        display: block;
        overflow: hidden;
        padding: 20px;
        border: 0px solid #ddd;
        margin-bottom: 30px;
        background-color: #eafaf1;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        border-radius: 0px;
    }

    .presentation img {
        max-width: 400px;
        height: auto;
        border-radius: 0px;
        margin: 5px;
        transition: transform 0.3s ease-in-out; /* Smooth hover effect */
        float: left; /* Default float for all images */
    }

    .presentation:nth-child(odd) img {
        float: right;
    }

    .presentation img:hover {
        transform: scale(1.1); /* Enlarge image on hover */
    }

    .presentation-content {
        display: block;
    }

    .presentation-title {
        font-size: 1.1em;
        font-weight: bold;
        margin-bottom: 5px;
        clear: both; /* Ensure it appears below the image */
    }

    .presentation-abstract {
        font-size: 1em;
        margin-top: 10px;
    }

    .presentation-image-info {
        text-align: left;
        font-size: 0.9em;
        color: #777;
        margin-top: 2px;
        padding: 0;
    }

    .presentation-info {
        margin: 1px 0;
        line-height: 1.2;
    }
</style>

# Presentation


<div class="presentation">
  <a href="https://docs.google.com/presentation/d/12nj4dgPJ6eTYF0ej4ER6HjwLEd9zI5WK/edit?usp=drive_link&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/CurvenoteTutorial.JPG" alt="CurvenoteTutorial">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">NCC lab meeting presentation (11/24)| Max Planck Institute for Empirical Aesthetics, Frankfurt, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Introducing curvenote and pylustrator </h3>
    <p class="presentation-abstract">
        In this meeting, I presented new tools I have recently discovered, making the process of writing a paper and creating  figures much more transparent, reproducible and 
        efficient with python. I first introduce the <a href="[url](https://curvenote.com/docs/publish/cli-overview)">curvenote</a> client, a tool that enables to integrate the output of Jupyter notebook cells in a separate markdown (MyST) that can be exported to
        papers templates from various journals. I then introduced the <a href="[url](https://pylustrator.readthedocs.io/en/latest/)">pylustrator</a> python package, which provides a GUI to organize figure panels and returns the modified matplotlib to generate the figure!
    </p>
  </div>
</div>


<div class="presentation">
  <a href="https://docs.google.com/presentation/d/1yfQzcyf-B8o9TB5DwVuaAd7veTf6mYdJ/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/ExperimentTestingFramework.jpg" alt="OSW_2024">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Open Science Workshop (2024) | Max Planck Institute for Empirical Aesthetics, Frankfurt, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Ensuring Experimental Integrity </h3>
    <p class="presentation-abstract">
        This workshop addresses the critical gap in testing and reporting experimental setups, a key but overlooked factor in the replication crisis. Participants will learn a practical framework to assess and document the performance of their experimental designs. Through hands-on exercises with tools like PsychoPy and Psychtoolbox, attendees will perform pre-run checks, execute experiments, analyze results, and share findings on protocols.io. By promoting transparency and reproducibility, this session equips researchers with essential skills to enhance research quality and foster collaboration across the field.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://docs.google.com/presentation/d/12HOAYTpHqJk23c1kug-GemE370DZX879/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/PUG_2024.JPG" alt="PUG_2024PUG_2024">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Psychology and brain conference (2024) | Psychology and brain conference, Hamburg, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Temporal dynamics of visual conscious experience </h3>
    <p class="presentation-abstract">
        This talk explored the neural dynamics involved in sustaining conscious perception beyond stimulus entry. In the first study, we found that activation in the posterior cortex was linked to stimulus duration, while the prefrontal cortex (PFC) showed only brief activation at the onset. The second study used the psychological refractory period (PRP) to investigate the coupling between experience and stimulus presentation, showing delays in reaction times for both stimulus onset and offset, suggesting a link between conscious experience and presentation dynamics. Combined, our results challenge the role of PFC as an NCC candidate. However, the lack of a PRP effect on short trials suggests that temporal coupling may not be systematic. To fully leverage the temporal dimension of experience to isolate the NCC, further studies resolving the dynamics of experience on a single-trial basis are required. 
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://docs.google.com/presentation/d/1bZPcWPBDkzx_2XsMNtL6zujB4J_Cp3eC/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/BU_Presentation.JPG" alt="BU_Presentation">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Guest talk (2023) | Centre for Human Brain Health, Birmingham University, U.K.</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Bayesian tools to investigate the neural correlates of sustained visual presentation</h3>
    <p class="presentation-abstract">
        In this talk, I focused on presenting novel statistical analysis tools to compute global amount of evidence for a given theory that formulated several predictions across several recording modalities and experiment. By leveraging recent advancements in Bayesian inference, it is possible to approximate the log of evidence for a particular model (i.e. Marginal likelihood) as the free energy. This quantity can then simply be summed across predictions and recording modalities and compared against an alternative model (whose predictions concerned the same data) to arbitrate between the two across all the data being investigated.  
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://docs.google.com/presentation/d/1YoTiGseyI7093GwbzbeCHxiHJ7_rhiVq/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/iEEGSeminar_2023.JPG" alt="iEEGSeminar_2023">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Tuesday Lunch Talk (2023) | iEEG Research Seminar, NYU Langone Health, USA</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Unraveling the Dynamics of Sustained Visual Experience: Exploring Neural Activation with Varying Stimulus Durations | Tuesday Lunch Talk, Max Planck institute for empirical aesthetics, 2023</h3>
    <p class="presentation-abstract">
        I presented the results of studies in which we explored the neural mechanisms that sustain conscious perception, beyond the initial entry into awareness. Using visual stimuli of different durations, alongside invasive electrophysiology and behavioral reports from epilepsy patients, we tested predictions from Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNW). We found sustained activation in posterior regions but only transient activation in the prefrontal cortex, suggesting it may not be crucial for consciousness. Additional behavioral tests indicated that conscious while participants consciously experience the onset and offset of the visual stimulus, the depth of conscious processing of the offset was much shallower and potentially not present on every single trial.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://docs.google.com/presentation/d/1cgVHgf6akIXfDXNbY5E1Ek9SYPp26f9s/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/TuesdayLunchTalk_2023.JPG" alt="TuesdayLunchTalk_2023">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Tuesday Lunch Talk (2022) | MPIAE, Frankfurt, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Refining our understanding of the neural mechanisms enabling consciousness by relying on theories predictive power</h3>
    <p class="presentation-abstract">
        In this talk, I present the result of my investigations regarding the neural mechanisms associated with conscious experience and highlight how we can rely on theories of consciousness to guide experiments and discoveries. For the most part, consciousness research has been conducted in a bottom up fashion, where experiments are being designed to isolate neural activity patterns that are systematically associated with consciousness. Based on the results of such experiments, theories of consciousness were formulated, proposing overarching mechanisms to be the source of consciousness. However, the field is currently fragmented, such that different theories are pursued in parallel, considering only part of the existing empirical evidence to be conclusive and discarding others based on methodological discords. In my research, I aim to help move the field forward by relying on a top down approach instead, whereby theories of consciousness formulate predictions a priori based on their current model. Failure to observe these predictions imply that the theories are at the very least incomplete and must be further refined.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://docs.google.com/presentation/d/1EKYt0GRoWMrSIlrjEksMhKPLE0ob7VyU/edit?usp=sharing&ouid=102857042721257996804&rtpof=true&sd=true">
    <img src="{{ site.baseurl }}/assets/PhDRetreat_2023.JPG" alt="PhDRetreat_2023">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">PhD Retreat (2022) | Freiburg, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Discussion and advice on how to facilitate working together in science</h3>
    <p class="presentation-abstract">
        In this workshop, I shared several practical advice with my fellow Phd colleagues on the few easy steps that can be taken to facilitates working together with other scientists (use git and github, define a clear data architecture a priori...)
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://ronyhirsch.github.io/collabconsciousness/">
    <img src="{{ site.baseurl }}/assets/ASSC2022_tutorial.JPG" alt="ASSC2022 tutorial">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">ASSC 25 (2022) | Amsterdam, Netherlands</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">A practical guide to collaborative consciousness science</h3>
    <p class="presentation-abstract">
      In this tutorial, we introduced our listeners to various challenges faced when embarking in a collaborative scientific exercise 
        and shared some of the solutions and wisdom we gained from engaging in one ourselves. I held this tutorial together with 
        <a href="https://www.arc-cogitate.com/tanya-brown">Tanya Brown</a>, 
        <a href="https://scholar.google.co.il/citations?user=Ie-iMfQAAAAJ&hl=en">Rony Hirschhorn</a>, 
        and <a href="https://scholar.google.com/citations?user=aI8u_WUAAAAJ&hl=en">Csaba Kozma</a>.
        </p>
  </div>
</div>


# Posters

<div class="presentation">
  <a href="https://drive.google.com/file/d/1FzdOdv7TBgsoojZd3WB85eGMDBsY6PvJ/view?usp=sharing">
    <img src="{{ site.baseurl }}/assets/PosterRetreat_2022.JPG" alt="PosterRetreat_2022">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">SAB meeting (2024) | MPIAE, Frankfurt, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Contrasting theories of consciousness </h3>
    <p class="presentation-abstract">
       This poster focused on testing competing theories of consciousness, Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNWT), through an adversarial collaboration within the COGITATE consortium. I present preliminary results of the iEEG recording modality, suggesting that while posterior electrodes activation correlates with stimulus duration, prefrontal activation does not. Supposing that participants did experience the persistence of the stimuli on the screen, these results challenge the role of the PFC as a neural correlate of conscious experience.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://drive.google.com/file/d/1FzdOdv7TBgsoojZd3WB85eGMDBsY6PvJ/view?usp=sharing">
    <img src="{{ site.baseurl }}/assets/ASSC2023_Poster.jpg" alt="ASSC2023_Poster">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">ASSC 25 (2023) | New York City, USA</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Variational RSA applied to iEEG data: accumulating evidences for theories to enable unbiased arbitration </h3>
    <p class="presentation-abstract">
        This poster focused on testing competing theories of consciousness, Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNWT), through an adversarial collaboration within the COGITATE consortium. We used multimodal data (fMRI, MEG, iEEG) and applied Bayesian statistics to compare evidence for each theory's predictions regarding neural activation and information representation during conscious perception. By integrating multiple predictions using variational representational similarity analysis (vRSA), this study offers a new approach to formally assess which theory better explains the neural mechanisms underlying consciousness.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://drive.google.com/file/d/1FzdOdv7TBgsoojZd3WB85eGMDBsY6PvJ/view?usp=sharing">
    <img src="{{ site.baseurl }}/assets/ASSC2023_Poster.jpg" alt="ASSC2023_Poster">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">MPIAE institute retreat (2023) | Riedberg, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Variational RSA applied to iEEG data: accumulating evidences for theories to enable unbiased arbitration </h3>
    <p class="presentation-abstract">
        This poster focused on testing competing theories of consciousness, Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNWT), through an adversarial collaboration within the COGITATE consortium. We used multimodal data (fMRI, MEG, iEEG) and applied Bayesian statistics to compare evidence for each theory's predictions regarding neural activation and information representation during conscious perception. By integrating multiple predictions using variational representational similarity analysis (vRSA), this study offers a new approach to formally assess which theory better explains the neural mechanisms underlying consciousness.
    </p>
  </div>
</div>


<div class="presentation">
  <a href="https://drive.google.com/file/d/1iPSMx5EeyEQYt3NOvwRM9n3WRJAZzMYY/view?usp=sharing">
    <img src="{{ site.baseurl }}/assets/Retreat_2024.JPG" alt="Retreat_2024">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">MPIAE institute retreat (2024) | Berlin, Germany</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Unravelling the temporal dynamics of visual conscious experience </h3>
    <p class="presentation-abstract">
        This poster addresses the challenge of understanding how the brain produces subjective experience, critiquing theories of consciousness for focusing too narrowly on the entry of content into awareness. By investigating the temporal dynamics of conscious experience, we explore new ways to test these theories. The first study presents results from the COGITATE project, testing predictions from Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNWT) regarding sustained visual presentation. The second study examines how events in a stream of images affect processing of subsequent stimuli, probing the temporal dynamics of consciousness.
    </p>
  </div>
</div>
