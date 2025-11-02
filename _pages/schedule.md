---
permalink: /schedule/
title: "Schedule - Winter School on Causality and Explainable AI"
author_profile: true
---

Provisional schedule.


<style>
/* 
.schedule {
  width: 100%;
  border-collapse: collapse;
  margin: 1.5rem 0;
  font-size: 0.95rem;
}
*/

.schedule {
  width: 75vw;   /* use full viewport width */
  margin-left: calc(-50vw + 50%); /* center it by shifting */
  margin: 1.25rem 0.25rem;
  font-size: 0.95rem;
}

.schedule th, .schedule td {
  border: 1px solid #ddd;
  padding: 0.75rem;
  text-align: center;
  vertical-align: middle;
}
.schedule th {
  background-color: #f5f5f5;
  font-weight: 700;
}
.schedule td {
  background-color: #fff;
}
.schedule .plenary {
  background-color: #eaf4ff;
  font-weight: 600;
  height: 2.5rem;
}
.schedule .lecture {
  background-color: #fdf6e3;
  font-weight: 600;
  height: 3.5rem;
}
.schedule .break {
  background-color: #f0f0f0;
  font-style: italic;
}
.schedule .lunch {
  background-color: #f9f9d1;
  font-weight: 600;
}
.schedule .buffet {
  background-color: #ffe6f2;  /* soft pink */
  font-weight: 600;
}
.schedule caption {
  caption-side: bottom;
  text-align: left;
  font-style: italic;
  margin-top: 0.5rem;
}
.schedule .contributed {
  background-color: #e6f9e6;
  font-weight: 500;
  height: 4.75rem;
  padding: 0;           /* remove extra padding so 100% really fills */
}
.schedule .contrib-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between; /* evenly distribute top & bottom */
  height: 100%;
}
.schedule .contrib-container div {
  flex: 1;                  /* each speaker gets half height */
  display: flex;            /* center text vertically */
  align-items: center;
  justify-content: center;  /* center text horizontally */
}

.schedule a {
  text-decoration: none;   /* remove underline */
  color: #333;             /* darker text */
  font-weight: 600;        /* semi-bold, less heavy than bold */
}
.schedule a:hover {
  text-decoration: underline; /* show underline only on hover */
  color: #000;                /* darker on hover */
}

.speaker-list {
  list-style: none;
  padding: 0;
  margin: 1rem 0;
}
.speaker-list li {
  padding: 0.4rem 0;
  border-bottom: 1px solid #eee;
}
.speaker-list li strong {
  font-size: 1.05em;
}
.speaker-role {
  color: #555;
  font-style: italic;
  margin-left: 0.3rem;
}
</style>



<table class="schedule">
  <thead>
    <tr>
      <th>Time</th>
      <th>Monday 20.10</th>
      <th>Tuesday 21.10</th>
      <th>Wednesday 22.10</th>
      <th>Thursday 23.10</th>
      <th>Friday 24.10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9:00–10:00</td>
      <td class="plenary"><a href="#gjergji-kasneci">Gjergji Kasneci (P)</a></td>
      <td class="plenary"><a href="#krikamol-muandet">Krikamol Muandet (P)</a></td>
      <td class="plenary"><a href="#gregoire-montavon">Grégoire Montavon (P)</a></td>
      <td class="plenary"><a href="#ulrike-von-luxburg">Ulrike von Luxburg (P)</a></td>
      <td>OFF</td>
    </tr>
    <tr>
      <td>10:00–10:30</td>
      <td class="break" colspan="5">Coffee break</td>
    </tr>
    <tr>
      <td>10:30–12:00</td>
      <td class="lecture"><a href="#julie-josse">Julie Josse (L)</a></td>
      <td class="lecture"><a href="#julie-josse">Julie Josse (L)</a></td>
      <td class="lecture"><a href="#ronan-sicre">Ronan Sicre (L)</a></td>
      <td class="lecture"><a href="#erwan-scornet">Erwan Scornet (L)</a></td>
      <td class="lecture"><a href="#erwan-scornet">Erwan Scornet (L)</a></td>
    </tr>
    <tr>
      <td>12:00–13:30</td>
      <td class="lunch" colspan="5">Lunch + Poster presentations</td>
    </tr>
    <tr>
      <td>13:30–15:00</td>
      <td class="lecture"><a href="#ronan-sicre">Ronan Sicre (L)</a></td>
      <td class="lecture"><a href="#erwan-scornet">Erwan Scornet (L)</a></td>
      <td><a href="#industry-side-event">Industry side-event</a></td>
      <td class="lecture"><a href="#ronan-sicre">Ronan Sicre (L)</a></td>
      <td class="plenary"><a href="#arthur-gretton">Arthur Gretton (P)</a></td>
    </tr>
    <tr>
      <td>15:00–15:30</td>
      <td class="break" colspan="5">Coffee break</td>
    </tr>
    <tr>
      <td>15:30–17:00</td>
      <td class="contributed">
        <div class="contrib-container">
          <div><a href="#moritz-willig">Moritz Willig (C)</a></div>
          <div><a href="#margaux-zaffran">Margaux Zaffran (C)</a></div>
        </div>
      </td> 
      <td class="contributed">
        <div class="contrib-container">
          <div><a href="#gabriele-ciravegna">Gabriele Ciravegna (C)</a></div>
          <div><a href="#martin-pawelczyk">Martin Pawelczyk (C)</a></div>
        </div>
      </td> 
      <td><a href="#industry-side-event">Industry side-event</a></td>
      <td class="contributed">
        <div class="contrib-container">
          <div><a href="#gian-marco-paldino">Gian Marco Paldino (C)</a></div>
          <div><a href="#jonas-wahl">Jonas Wahl (C)</a></div>
        </div>
      </td> 
      <td>OFF</td>
    </tr>
    <tr>
    <td>17:30–20:00</td>
    <td class="buffet"><a>Welcoming Buffet</a></td>
    <td>OFF</td>
    <td>OFF</td>
    <td>OFF</td>
    <td>OFF</td>
    </tr>
  </tbody>
  <caption>P = Plenary, L = Lecture, C = Contributed</caption>
</table>


---

## <a id="industry-side-event"></a>Industry side-event

The industry side-event will highlight how research in causality and explainable AI translates into real-world impact through contributed talks and exchanges with industry researchers. This session offers participants a unique opportunity to see how theory and methodological advances connect to practice, explore career pathways, and engage directly with practitioners driving innovation in AI.

List of confirmed speakers:

* <a href="#audrey-annabelle">Audrey Poinsot et Annabelle Blangero</a>  (Ekimetrics)

* <a href="#aurore-lomet">Aurore Lomet</a> (CEA)

* <a href="#fabien-faivre">Fabien Faivre</a> (MACIF)

* <a href="#nicolas-bousquet">Nicolas Bousquet</a> (EDF)


<!--
<details>
  <summary><strong><a href="#audrey-annabelle">Audrey Poinsot et Annabelle Blangero</a></strong>  (Ekimetrics)</summary>
</details>
<details>
  <summary><strong><a href="#nicolas-bousquet">Nicolas Bousquet</a></strong>(EDF)</summary>
</details>
<details>
  <summary><strong><a href="#aurore-lomet">Aurore Lomet</a></strong>(CEA)</summary>
</details>
-->




---

## Abstracts


### <a id="arthur-gretton"></a>Arthur Gretton: *Causal Effect Estimation with Context and Confounders*
**Abstract**: A fundamental causal modelling task is to predict the effect of an intervention (or treatment) on an outcome, given context/covariates. Examples include predicting the effect of a medical treatment on patient health given patient symptoms and demographic information, or predicting the effect of ticket pricing on airline sales given seasonal fluctuations in demand. The problem becomes especially challenging when the treatment and context are complex (for instance, "treatment" might be a web ad design or a radiotherapy plan), and when only observational data is available (i.e., we have access to historical data, but cannot intervene ourselves). The challenge is greater still when the covariates are not observed, and constitute a hidden source of confounding. I will give an overview of some practical tools and methods for estimating causal effects of complex, high dimensional treatments from observational data. The approach is based on conditional feature means, which represent conditional expectations of relevant model features. These features can be deep neural nets (adaptive, finite dimensional, learned from data), or kernel features (fixed, infinite dimensional, enforcing smoothness). When hidden confounding is present, a neural net implementation of instrumental variable regression can be used to correct for this confounding. The methods will be applied to modelling employment outcomes for the US Job Corps program for Disadvantaged Youth, and in policy evaluation for reinforcement learning.


*The slides of the talk can be found [here](https://www.gatsby.ucl.ac.uk/~gretton/coursefiles/paris25_course.pdf).*


### <a id="erwan-scornet"></a>Erwan Scornet: *Explainability via tree-based methods*
**Abstract**: In many sensitive areas like medicine, designing an algorithm with good predictive performances is not enough: there is a need to understand the decision process at work inside the algorithm to check for undesirable behavior (e.g., fairness issues) or to gain knowledge about the underlying phenomenon. Numerous (heuristical) tools have been proposed to open black-box algorithms in order to understand their prediction. Variable importances are among the most explainable tools as they are generally easy to compute and understand at first sight. In this lecture, we will talk about tree-based methods and how variable importances can be used to provide (un)clear explanations about their decision process. We will also take a look at decision rules that can directly provide interpretable predictions.

*The lecture slides can be found [here](/files/Erwan_presentation.pdf).*



### <a id="fabien-faivre"></a>Fabien Faivre: *Causality? What good is IT for an actuary?*
**Abstract**: Actuaries are a centerpiece of any insurance company risk management framework. Actuaries are traditionally in charge of risk assessment for technical pricing and thoughout the years extended their presence to reserving, economic capital evaluation or Assel Liability Management. They routinely suggest risk mitigation strategies be it through reinsurance program design or other means as appropriate. However, despite their skills in statistics, and over the recent years, data science, a nagging gap remains in their training: the absence of any formal causal course syllabus. This talk will go over a personnal journey towards the discovery of causality, potential application for insurance company and the work being currently set up at Macif, a French mutual insurance company, at the interplay of climate risk, prevention and actuarial science.


### <a id="gabriele-ciravegna"></a>Gabriele Ciravegna: *Accurate, Interpretable, Verifiable CBMs*
**Abstract**: I will present a concise overview of a research trajectory aimed at making Concept Bottleneck Models (CBMs) accurate, interpretable, and verifiable. CBMs are transparent neural networks as they predict a set of human-understandable concepts before producing the final output. However, early CBMs faced a trade-off between accuracy and transparency. Concept Embedding Models (CEMs) addressed this by learning rich, high-dimensional concept representations that enable test-time interventions without sacrificing performance. Yet, both CBMs and CEMs mainly rely on black-box task predictors, limiting their interpretability. The Deep Concept Reasoner (DCR) introduced a neural-symbolic layer that constructs logic rules over concepts for prediction, achieving full transparency but lacking formal verifiability. The Concept-based Memory Reasoner (CMR) resolves this by incorporating a memory of trainable rules, enabling formal verification, rule-level interventions, and pre-deployment checks. Notably, CMR integrates all three properties, representing an accurate, interpretable, and verifiable CBM.


### <a id="gian-marco-paldino"></a>Gian Marco Paldino: *Causal Discovery in Multivariate Time Series through Mutual Information Featurization*
**Abstract**: Our work addresses the fundamental challenge of discovering causal relationships in complex multivariate time series. Traditional methods often struggle with restrictive linear assumptions or become uninformative in the presence of intricate, non-linear dynamics. We propose Temporal Dependency to Causality (TD2C), a supervised learning framework that shifts from statistical testing to pattern recognition. TD2C learns to recognize causal signatures from information-theoretic and statistical descriptors, demonstrating remarkable zero-shot generalization and state-of-the-art performance, particularly in high-dimensional and non-linear settings. (**Related paper**: https://arxiv.org/abs/2508.01848)

*The slides of the talk can be found [here](https://www.researchgate.net/publication/396933445_Causal_Discovery_in_Multivariate_Time_Series_through_Mutual_Information_Featurization).*


### <a id="gjergji-kasneci"></a>Gjergji Kasneci: *Structure-Aware Actionable Recourse and Graph Counterfactuals*
**Abstract**: Modern AI must answer two user-centric questions: why did I get this outcome? and what can I change to obtain a better one? We begin with algorithmic recourse and show that feasible interventions must respect statistical dependencies and uncertainty; otherwise, “advice” breaks under recalibration, deletion, or user noise. Beyond tabular settings, we analyze counterfactual explanations in graph data, where dependencies are explicit via edges but structural plausibility is brittle and often dynamic. We introduce structure-aware counterfactuals that preserve global spectral style while adjusting local content to flip a model’s decision. This results in valid, faithful explanations and actionable guidance for end-users across diverse graph domains.


### <a id="gregoire-montavon"></a>Grégoire Montavon: *Uncovering input-target associations with Explainable AI*
**Abstract**: Explainable AI (XAI) has become an essential technology for promoting transparency in machine learning (ML). However, Explainable AI offers more than just a framework for verifying ML models. It also provides a fitting framework for identifying input-target relationships in a broader range of systems of interest. Unlike basic correlational analyses, an XAI algorithm combined with a powerful ML model can filter out weak correlates in the data and identify combinations of input variables that are the most predictive. In this talk, I will present recent applications of this approach in the context of cancer to improve understanding of regulatory networks and treatment outcomes. In the second part of the presentation, I will transition from input-target relationships to input-uncertainty relationships (e.g. in electricity markets) and demonstrate how Explainable AI methods can be tailored for this type of analysis.


### <a id="jonas-wahl"></a>Jonas Wahl: *Are our DAGs correct? Recent developments in causal discovery evaluation*
**Abstract**: Causal graphical models are considered important tools to integrate expert knowledge into statistical data analysis. As a consequence, practitioners often face the challenge to evaluate the quality of their hypothesized causal models. This issue becomes particularly salient for causal graphical models obtained through a causal discovery method in which case most or all of the available data has already been used in the discovery task. In this talk, we will review recent developments regarding the evaluation of causal structure learning methods and the quality of their outputs. In particular, we will discuss to which degree assumption violations can be detected in causal discovery and how method testing often introduces additional assumptions that need to be weighted carefully against the assumptions of the initial learning algorithm.

*The slides of the talk can be found [here](/files/Jonas_Paris_2025.pdf).*



### <a id="julie-josse"></a>Julie Josse: *Personalized Care Through Causal & Federated Learning: From Data to Decisions*
**Abstract**: Understanding how to generalize causal conclusions beyond the sample of a randomized controlled trial (RCT) is a key challenge in modern causal inference. Traditional RCTs, while rigorous, often suffer from limited external validity: their participants do not always represent the real-world populations where medical decisions must be made. Generalization, or transportability methods, provide a principled way to bridge this gap. They allow researchers to transport treatment effect estimates from a study population to new target populations that may differ in their covariate distributions. In doing so, they offer an alternative perspective to traditional meta-analysis, the current gold standard in evidence-based medicine.In this tutorial, we introduce a unified framework for generalizing a broad class of first-moment causal effect measures (including, but not limited to, the risk difference and risk ratio) under covariate shift. We outline the key assumptions required, discuss identification and estimation strategies, and provide intuitive guidance on when and how these methods can be reliably applied in practice. Finally, we extend the discussion to settings where evidence arises from multiple clinical trials. We show how causal federated learning can be leveraged to aggregate information across distributed sources, enabling collaborative inference without direct data sharing.

*The lecture slides can be found [here](https://juliejosse.com/wp-content/uploads/2025/10/CausalXAI21oct2025.pdf).*



### <a id="krikamol-muandet"></a>Krikamol Muandet: *An Explanation Game: From Mechanistic Interpretability to Strategic Explanation Design*
**Abstract**: A good explanation enables effective communication, but a great one shapes behaviour. Hence, it should not only be faithful to the internal mechanisms it seeks to elucidate but also serve as an instrument to inform, convince, and guide others toward desirable actions. In this talk, I will first show how tools from causal inference can be used to systematically examine the relationship between a model’s predictions and its explanations. Specifically, we study the relationship between explanations and predictions by measuring the treatment effects of interventions on their causal ancestors—such as hyperparameters and inputs used to generate saliency-based explanations. Our results reveal that the alignment between explanation and prediction is far from ideal, and that this gap widens for higher-performing models—the very models most likely to be deployed. I will then turn to the problem of explanation design in algorithmic decision-making with strategic agents. In this setting, explanations themselves become part of an interactive game. I will highlight two key challenges that emerge: competitive selection and the sufficiency of partial explanation design, and discuss how these challenges shape our understanding of explanations as both epistemic and strategic objects.



### <a id="martin-pawelczyk"></a>Martin Pawelczyk: *Efficiently Verifiable Proofs of Data Attribution*
**Abstract**: Data attribution methods aim to answer useful counterfactual questions like "what would a ML model's prediction be if it were trained on a different dataset?" However, estimation of data attribution models through techniques like empirical influence or "datamodeling" remains very computationally expensive. This causes a critical trust issue: if only a few computationally rich parties can obtain data attributions, how can resource-constrained parties trust that the provided attributions are indeed "good," especially when they are used for important downstream applications (e.g., data pricing)? In this paper, we address this trust issue by proposing an interactive verification paradigm for data attribution. An untrusted and computationally powerful Prover learns data attributions, and then engages in an interactive proof with a resource-constrained Verifier. Our main result is a protocol that provides formal completeness, soundness, and efficiency guarantees in the sense of Probably-Approximately-Correct (PAC) verification. Importantly, our protocol ensures the Verifier's workload, measured by the number of independent model retrainings it must perform, scales only as O(1/epsilon); i.e., independently of the dataset size.



### <a id="moritz-willig"></a>Moritz Willig: *Beyond Causal Parrots: The Role of Meta-Causality for Genuine Causal Understanding*
**Abstract**: The majority of today's machine learning models are trained using associational methods, raising fundamental questions about their ability to advance beyond the first rung of the causal ladder. While natural language allows for the expression of higher-level causal facts within training data, large language models often still act as mere "Causal Parrots". They mimic causal language but lack an understanding of the underlying mechanisms. This prompts a fundamental question: can systems achieve genuine understanding without knowing how their own (causal) knowledge is formed? In this talk, I introduce Meta-Causal Models, a novel framework designed to explicitly model and reason about the emergence and change of causal relationships. I demonstrate its power through applications in qualitative modeling, attribution under switching causal relations, and adaptive decision-making. Ultimately, I argue that meta-causal understanding may be the dividing line between systems that merely describe the world from those that truly understand it.

*The slides of the talk can be found [here](/files/Moritz_XAICausalWinterSchool.pdf).*



### <a id="nicolas-bousquet"></a>Nicolas Bousquet: *An overview of works on AI explainability for critical systems at EDF*
**Abstract**: The use of AI tools to support the management of existing critical systems or to explore new scenarios represents a major challenge for an energy company such as EDF. Over the past several years, alongside the growing development of AI-based tools aimed at improving the management of electricity production, distribution, and consumption, EDF — in close collaboration with its scientific partners — has made significant investments in the critical analysis, methodological advancement, and dissemination of knowledge on explainability-related topics. This presentation aims to summarize this ongoing effort, highlight the major scientific and operational results achieved, and provide an overview of the key research currently underway.



### <a id="ronan-sicre"></a>Ronan Sicre: *Visual explainability*
**Abstract**: This course aims at giving a panorama of XAI methods applied to visual recognition models. We will first introduce the computer vision fields through the many tasks that are studied in the field. We will then detail the specifics of convolutional architectures, then detail a number of post-hoc methods designed for such models. We will later focus on the evaluation of these methods, with some discussions. Then, we will study transformers architectures and present post-hoc methods designed for such models. We will then move to transparency and hybrid methods, before discussing prototypes and part-based methods. Finally, we will study concept-based XAI, the taxonomy and several existing methods.

*Links to the lecture slides (also available at [Ronan's webpage](https://www.irit.fr/~Ronan.Sicre/enseignement/)):*

- [Part1](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part1_XAI-intro.pdf): XAI intro 

- [Part2](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part2_CV-intro.pdf): Computer vision intro

- [Part3](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part3_conv.pdf): Convolution an CNN architectures

- [Part4](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part4_Posthoc-conv.pdf): Posthoc methods for CNNs

- [Part5](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part5_Posthoc-trans.pdf): Transformers model and posthoc methods

- [Part6](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/Part6_tranp-parts.pdf): Transparency with parts

- [Part7](https://www.irit.fr/~Ronan.Sicre/wp-content/uploads/sites/249/2025/10/part7_CXAI.pdf): Concept-based XAI 




### <a id="ulrike-von-luxburg"></a>Ulrike von Luxburg: *Informative explanations only exist for simple functions*
**Abstract**: Many researchers have suggested that local post-hoc explanation algorithms can be used to gain insights into the behavior of complex machine learning models. However, theoretical guarantees about such algorithms only exist for simple decision functions, and one might wonder why is this the case. In my talk I'll introduce a general, learning-theory-based framework for what it means for an explanation to provide information about a decision function. With this approach, we show that many popular explanation algorithms are not informative when applied to complex decision functions, providing a rigorous mathematical rejection of the idea that it should be possible to explain any model. 

*Related paper: [https://arxiv.org/abs/2508.11441](https://arxiv.org/abs/2508.11441).*






