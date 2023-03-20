---
layout: default
permalink: /

speakers:
  - name: Alexander Gray
    url: https://research.gatech.edu/data/seminar-series/alexander-gray
    affiliation: IBM Thomas J. Watson Research Center
    image: assets/img/Alexander_Gray.jpg

  - name: Benjamin Rosman
    url: https://www.benjaminrosman.com/
    affiliation: University of the Witwatersrand
    image: assets/img/Benjamin_Rosman.jpg

  - name: Céline Hocquette
    url: https://cs.brown.edu/people/gdk/
    affiliation: University of Oxford
    image: assets/img/Celine_Hocquette.jpg

  - name: George Konidaris
    url: https://cs.brown.edu/people/gdk/
    affiliation: Brown University
    image: assets/img/George_Konidaris.jpg

  - name: Lise Getoor
    url: https://getoor.linqs.org/
    affiliation: UC, Santa Cruz <br> <i>(invited)</i>
    image: assets/img/Lise_Getoor.jpg

  - name: Sheila McIlraith
    url: https://www.cs.toronto.edu/~sheila/
    affiliation: University of Toronto
    image: assets/img/Sheila_McIlraith.jpg

  - name: Swarat Chaudhuri
    url: https://www.cs.utexas.edu/~swarat/
    affiliation: University of Texas
    image: assets/img/Swarat_Chaudhuri.png

organizers:
  - name: Alessandra Russo
    url: http://wp.doc.ic.ac.uk/arusso/
    affiliation: Imperial College London
    image: assets/img/Alessandra_Russo.jpg

  - name: Daiki Kimura
    url: https://researcher.watson.ibm.com/researcher/view.php?person=jp-DAIKI
    affiliation: IBM Research - Tokyo <br> <i>(primary contact)</i>
    image: assets/img/Daiki_Kimura.jpg

  - name: Ndivhuwo Makondo
    url: https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Ndivhuwo.Makondo
    affiliation: IBM Research - Africa
    image: assets/img/Ndivhuwo_Makondo.jpg

  - name: Steven James
    url: https://www.wits.ac.za/staff/academic-a-z-listing/j/stevenjameswitsacza/
    affiliation: University of the Witwatersrand
    image: assets/img/Steven_James.jpg

pcs:
  - name: Asim Munawar
    affiliation: IBM Thomas J. Watson Research Center

  - name: Don Joven Ravoy Agravante
    affiliation: IBM Research - Tokyo

  - name: Geraud Nangue Tasse
    affiliation: Univ. of the Witwatersrand

  - name: Jiayuan Mao
    affiliation: Massachusetts Institute of Technology

  - name: Kyle Harper Erwin
    affiliation: IBM Research - Africa

  - name: Michiaki Tatsubori
    affiliation: IBM Research - Tokyo

  - name: Minori Narita
    affiliation: University of Toronto

  - name: Naweed Aghmad Khan
    affiliation: IBM Research - Africa

  - name: Sarathkrishna Swaminathan
    affiliation: IBM Research - Almaden

  - name: Subhajit Chaudhury
    affiliation: IBM Thomas J. Watson Research Center
---

# Workshop Description

Deep Reinforcement Learning (RL) has been widely applied to many applications in various domains including computer games, language, vision, and real robot control (Mnih et al., 2015; Narasimhan et al., 2015; Yuan et al., 2018). In real-world applications, state of the art RL algorithms still face some challenges, including sample inefficiency, explainability of the learned policy, partial observability, dynamic environments, sparse rewards, and safety constraints. For example, these methods require many training trials to converge to the optimal action policy due to extremely large state spaces from the environment. Moreover, even if the algorithm converges, the trained action policy is not understandable to human operators because the policy is stored in a black-box deep neural network. These issues become critical when human operators want to verify the trained rules, control the trained agent, and to add action restrictions.

In order to address these issues, reinforcement learning methods which introduce symbolic representations and reasoning in deep complex network have been proposed in Dong et al. (2019); Anderson et al. (2020); Kimura et al. (2021); Chaudhury et al. (2021). Neural Logic Machine (NLM, Dong et al. (2019)) incorporates a neural-symbolic architecture for both inductive learning and logic reasoning, using tensors to represent logic predicates. Reinforcement Learning with Formally Verified Exploration (REVEL, Anderson et al. (2020)) has two policy classes: a general, neurosymbolic class with approximate gradients and a more restricted class of symbolic policies that allows efficient verification. Neuro-Symbolic Reinforcement Learning with First-Order Logic in LNN (FOL-LNN, Kimura et al. (2021)) proposes an algorithm for extracting first-order logical facts from text observation and external word meaning network, and trains a policy using logical neural network (LNN, Riegel et al. (2020)) with directly interpretable logical operators. SymboLic Action policy for Textual Environments (SLATE, Chaudhury et al. (2021)) learns interpretable action policy rules from symbolic abstractions of textual observations for improved generalization. These methods are generally called “Neuro-Symbolic Reinforcement Learning”, and they combine knowledge-driven symbolic reasoning and data-driven machine learning approaches.

We believe that incorporating symbolic representations and reasoning into deep learning can potentially solve many of the challenges facing action decision making and reinforcement learning. The primary goal of this workshop is to facilitate community building: we hope to bring researchers together to consolidate this line of research and foster collaboration in the community.

In this workshop, we will cover following challenges in decision making and RL:

- **Neuro-Symbolic Agents**
- **Neuro-Symbolic Reinforcement Learning**
- **Neuro-Symbolic Chat Bot**
- **Safe Reinforcement Learning by Neuro-Symbolic Approach**
- **Explainability through Neuro-Symbolic Reinforcement Learning**
- **Neuro-Symbolic Model-based Reinforcement Learning**
- **Decision Making by Planning with Neuro-Symbolic Approaches**

{: #cfp }

# Call for Paper (tentative)

We welcome original research papers ranging between **4-8 pages** in length (not including references or supplementary materials) which is formatted according to the IJCAI guidelines [link](https://www.ijcai.org/authors_kit).

We also welcome extended abstracts of up to **2 pages** (not including references) that describe open problems and challenges in the area of Neuro-Symbolic Agent.

The papers will be non-archival, which means we welcome papers that have been published or submitted to other conferences and journals. However, authors are required to acknowledge their papers’ original appearance in such cases.

All accepted papers and extended abstracts will be presented as posters.

The program committee will select a few papers for oral presentation.
There will be a poster session during the scheduled coffee breaks to facilitate and spark discussions amongst attendees.

# Important Dates

- Submission deadline: April 26th, 2023 (11:59 pm AOE)
- Acceptance notification: June 1st, 2023
- Camera ready for accepted submissions: TBA (around June 15th, 2023)
- Workshop date: TBA

{: #invited }

# Invited Talks (tentative)

<div class="row justify-content-center">
  {% for p in page.speakers %}
  <div class="col-lg-3 text-center">
    <div class="member-box">
      <div class="member-image">
        <a href="{{ p.url }}">
        <img alt="{{ p.name }}" class="img-fluid mb-2" style="height: 180px;" src="{{ p.image }}" />
        </a>
      </div>
      <div class="member-meta">
        <a href="{{ p.url }}">{{ p.name }}</a><br>
        {{ p.affiliation }}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="text-center"> * in alphabetical order</div>

{: #organizers }

# Organizers

<div class="row justify-content-center">
  {% for p in page.organizers %}
  <div class="col-lg-3 text-center">
    <div class="member-box">
      <div class="member-image">
        <a href="{{ p.url }}">
        <img alt="{{ p.name }}" class="img-fluid mb-2" style="height: 180px;" src="{{ p.image }}" />
        </a>
      </div>
      <div class="member-meta">
        <a href="{{ p.url }}">{{ p.name }}</a><br>
        {{ p.affiliation }}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="text-center"> * in alphabetical order</div>

{: #pc }

# Program Committee (tentative)

{% for p in page.pcs %}

- {{p.name}} ({{p.affiliation}})
  {% endfor %}

<div class="text-center"> * in alphabetical order</div>

### Reference

- Anderson, G., Verma, A., Dillig, I., and Chaudhuri, S., "Neurosymbolic reinforcement learning with formally verified exploration", NeurIPS 2020.
- Chaudhury, S., Sen, P., Ono, M., Kimura, D., Tatsubori, M., and Munawar, A., "Neuro-symbolic approaches for text-based policy learning", EMNLP 2021.
- Dong, H., Mao, J., Lin, T., Wang, C., Li, L., and Zhou, D., "Neural logic machines", ICLR 2019.
- Kimura, D., Ono, M., Chaudhury, S., Kohita, R., Wachi, A., Agravante, D. J., Tatsubori, M., Munawar, A., and Gray, A., "Neuro-symbolic reinforcement learning with first-order logic", EMNLP 2021.
- Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., Graves, A., Riedmiller, M. A., Fidjeland, A., Ostrovski, G., Petersen, S., Beattie, C., Sadik, A., Antonoglou, I., King, H., Kumaran, D., Wierstra, D., Legg, S., and Hassabis, D., "Human-level control through deep reinforcement learning", Nature 2015.
- Narasimhan, K., Kulkarni, T. D., and Barzilay, R., "Language understanding for text-based games using deep reinforcement learning", EMNLP 2015.
- Riegel, R., Gray, A. G., Luus, F. P. S., Khan, N., Makondo, N., Akhalwaya, I. Y., Qian, H., Fagin, R., Barahona, F., Sharma, U., Ikbal, S., Karanam, H., Neelam, S., Likhyani, A., and Srivastava, S. K., "Logical neural networks", arXiv 2020.
- Yuan, X., Côté, M., Sordoni, A., Laroche, R., des Combes, R. T., Hausknecht, M. J., and Trischler, A., "Counting to explore and generalize in text-based games", arXiv 2018.
