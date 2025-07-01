---
title: 
feature_text: |
   
feature_image: "/assets/banner/banner_github.jpg"
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


# Upcoming

## Articles
- Zeidman, P., Lepauvre, A., Melloni, L., Friston, K. Variational Representation Similarity Analysis (vRSA) for EEG/MEG, *in prep*
- Lepauvre, A., Engeser, M., Dehaene, M., Melloni, L. Investigating the timing of conscious experience using a dual-task paradigm and quantified introspection. *in prep*
- Seedat, A., Lepauvre, A., Jeschke, J., Gorska-Klimowska, U., et al. Open multi-center iEEG dataset with task probing conscious visual perception (2024). Submitted at Scientific data

## Book 
<div class="presentation">
  <a href="https://alexlepauvre.github.io/variation_laplace_for_dummies/intro.html">
    <img src="{{ site.baseurl }}/assets/VLFordummies.jpg" alt="VLFordummies">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Alex Lepauvre, Jan-Gabriel Hartel | (IN PREP)</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Variational Laplace for dummies</h3>
    <p class="presentation-abstract">
      Thanks to the Bayes theorem, it is possible to compute the (posterior) probability of parameters given observed data. Many have argued in recent years that Bayesian inference should 
      supplant frequentist statistics. The adoption of Bayesian inference has however been limited, due to the perceived complexity of the approach, which often requires the use of complex sampling procedure to approximate unkown quantities. Variational Laplace offers an alternative to these computational approaches and readily offers alternatives to the frequentist statistical tests routinely used in neuroscience (GLM, mutlivariate pattern analyses). This method is however often discussed in highly technical papers, which may be intimidating to most readers. In this book, we demystify variational Laplace by presenting it in an intuititive and accessible fashion. Starting from the simplest possible statistical model (linear regression) most reader will be familiar with, we work our way up through verbal explanation, code examples and mathematical formulae. Whether you're a student, researcher, or curious thinker, this book will help you build a solid understanding of variational inference without getting lost in dense equations.
        </p>
  </div>
</div>

# Published
<div class="presentation">
  <a href="https://link.springer.com/article/10.3758/s13428-024-02508-y">
    <img src="{{ site.baseurl }}/assets/FrameworkFlowChart.jpg" alt="FrameworkFlowChart">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Behavioral research method, Alex Lepauvre, Rony Hirschorn, Katarina Bendtz, Liad Mudrik, Lucia Melloni | 2024</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">A standardized framework to test event-based experiments</h3>
    <p class="presentation-abstract">
      The replication crisis in psychology and neuroscience has highlighted the need for better scientific practices, such as preregistration. However, less attention has been given to testing and reporting the accuracy of experimental setups. In this work, we propose a framework for testing setups across multiple labs, including EEG, MEG, and fMRI. A survey of 100 researchers revealed that most test their setups, but few publish their results. We demonstrate how even small inaccuracies can impact outcomes and offer a standardized, open-source protocol to improve reproducibility and research quality across studies.
        </p>
  </div>
</div>

<div class="presentation">
  <a href="https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00162/120746/Relevance-acquisition-through-motivational">
    <img src="{{ site.baseurl }}/assets/PaperGoettingen.JPG" alt="PaperGoettingen">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Imaging Neuroscience, Francesco Grassi, Louisa Kulke, Alex Lepauvre, Anne Schacht | 2024</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">Relevance acquisition through motivational incentives: Modeling the time-course of associative learning and the role of visual features</h3>
    <p class="presentation-abstract">
      Motivational relevance associated with symbolic stimuli affects both neural and behavioral responses, similar to stimuli with inherent emotional value. However, the impact of this relevance on early sensory stages and lexico-semantic processing is unclear. Using an associative learning paradigm, we manipulated visual features of pseudowords associated with gain, loss, or neutral outcomes. During learning and test phases, pupil responses and brain activity (P1, EPN, LPC, P3) were measured. Loss associations showed stronger pupil responses and neural activation in early visual and lexico-semantic processing. Gain associations had the most substantial impact on processing during the test phase, while visual feature congruence influenced the same processes without overlapping with motivational relevance effects.
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://www.biorxiv.org/content/10.1101/2023.06.23.546249v2.abstract">
    <img src="{{ site.baseurl }}/assets/Cogitate.JPG" alt="Cogitate">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">BiorXiv, Cogitate Consortium, et al. | 2023</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">An adversarial collaboration protocol for testing contrasting predictions of global neuronal workspace and integrated information theory</h3>
    <p class="presentation-abstract">
      Different theories propose how subjective experience arises from brain activity, yet confirmation bias and design choices hinder progress. In an open science adversarial collaboration, we directly compare Integrated Information Theory (IIT) and Global Neuronal Workspace Theory (GNWT). Using a theory-neutral approach, 256 subjects viewed stimuli while brain activity was measured via fMRI, MEG, and electrocorticography. We found content-related activity in visual and frontal areas, with sustained responses in occipital and temporal cortex reflecting stimulus duration. While some predictions were confirmed, both theories faced significant challenges. This collaboration highlights the value of a theory-driven, systematic approach to advance neuroscience.
        </p>
  </div>
</div>

<div class="presentation">
  <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0268577">
    <img src="{{ site.baseurl }}/assets/cogitate_protocol.JPG" alt="cogitate_protocol">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Plos One, Lucia Melloni, et al. | 2023</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">An adversarial collaboration protocol for testing contrasting predictions of global neuronal workspace and integrated information theory.</h3>
    <p class="presentation-abstract">
      The relationship between conscious experience and brain activity has long intrigued scientists. Multiple theories have emerged, but they often develop in isolation. To advance research, we initiated an adversarial collaboration between proponents of two major theories—Global Neuronal Workspace and Integrated Information Theory. Together, we designed two experiments that test the differing predictions of these theories about the neural correlates of visual consciousness. Six impartial laboratories will follow a preregistered protocol using fMRI, M-EEG, and iEEG. This large-scale collaboration aims to provide decisive evidence and offer a model for open, theory-driven science
    </p>
  </div>
</div>

<div class="presentation">
  <a href="https://philosophymindscience.org/index.php/phimisci/article/view/9151">
    <img src="{{ site.baseurl }}/assets/NCCPaper.JPG" alt="NCCPaper">
  </a>
  <div class="presentation-image-info">
    <p class="presentation-info">Philosophy and the Mind Sciences 2, Alex Lepauvre, Lucia Melloni | 2021</p>
  </div>
  <div class="presentation-content">
    <h3 class="presentation-title">The search for the neural correlate of consciousness: Progress and challenges</h3>
    <p class="presentation-abstract">
      Twenty years ago, Thomas Metzinger's book "The Neural Correlates of Consciousness" reviewed the state of consciousness studies from both philosophical and empirical perspectives. Since then, numerous empirical studies have identified many candidate neural correlates of consciousness, yet no consensus has been reached. The field faces persistent methodological challenges, and the proliferation of theories contrasts with limited compelling data. The foundational contrastive method has also been criticized, but few alternatives have been pursued. We propose three key methodological shifts: expanding beyond the contrastive method, sharing data through centralized databases, and directly comparing theories to reduce fragmentation and promote progress toward explaining consciousness.
    </p>
  </div>
</div>
