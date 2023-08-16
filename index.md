---
layout: default
permalink: /

speakers:
  - name: Alexander Gray
    url: https://research.gatech.edu/data/seminar-series/alexander-gray
    affiliation: IBM Thomas J. Watson Research Center
    image: assets/img/Alexander_Gray.jpg

  - name: Luc De Raedt
    url: https://wms.cs.kuleuven.be/people/lucderaedt
    affiliation: KU Leuven
    image: assets/img/Luc_De_Raedt.jpg

  - name: Wang-Zhou Dai
    url: https://daiwz.net/
    affiliation: Nanjing University
    image: assets/img/WangZhou_Dai.jpg

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
  - name: Divanisha Patel
    affiliation: University of the Witwatersrand

  - name: Geraud Nangue Tasse
    affiliation: University of the Witwatersrand

  - name: Jiayuan Mao
    affiliation: Massachusetts Institute of Technology

  - name: Kyle Harper Erwin
    affiliation: IBM Research - Africa

  - name: Minori Narita
    affiliation: University of Toronto

  - name: Naweed Aghmad Khan
    affiliation: IBM Research - Africa

  - name: Sarathkrishna Swaminathan
    affiliation: IBM Research - Almaden

  - name: Tristan Bester
    affiliation: University of the Witwatersrand
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

# Call for Paper

We welcome original research papers ranging between **4-8 pages** in length (not including references or supplementary materials) which is formatted according to the IJCAI guidelines [link](https://www.ijcai.org/authors_kit). Reviews are **double blind**, so no identifying information should be on the papers.

Please submit your paper at here: [Microsoft CMT site](https://cmt3.research.microsoft.com/NSAIJCAI2023/Submission/Index)

We also welcome extended abstracts of up to **2 pages** (not including references) that describe open problems and challenges in the area of Neuro-Symbolic Agent.

The papers will be non-archival, which means we welcome papers that have been published or submitted to other conferences and journals. However, authors are required to acknowledge their papers’ original appearance in such cases.

All accepted papers and extended abstracts will be presented as posters.

The program committee will select some papers for oral presentation.
There will be a poster session during the scheduled coffee breaks to facilitate discussions among attendees.

**Summary:**

- **Length: 4-8 pages (research paper), or 2 pages (extended abstract)**
- **Double blind**
- **Two types of accept: Accept (oral & poster), Accept (poster)**
- **Submission site: [Microsoft CMT site](https://cmt3.research.microsoft.com/NSAIJCAI2023/Submission/Index)**

{: #dates }

# Important Dates

- Submission deadline: **May 25th, 2023 (11:59 pm AOE)**
- Acceptance notification: **June 5th, 2023**
- Camera ready for accepted submissions: **June 20th, 2023 (11:59 pm AOE)**
- Workshop date: **August 20th, 2023: Workshop W26 @ Almaty 6006**

{: #papers }

# Accepted papers

#### Oral and Poster

- Minori Narita, and Daiki Kimura, "Introducing Trial-and-Error Exploration to Avoid Critical Failure for Efficient Reinforcement Learning"
- Jaeil Park, and Sung-Bae Cho, "[A Neuro-Symbolic Approach with Reinforcement Learning for Explainable Question Answering in Pedestrian Anomaly Video Sequence](assets/papers/A Neuro-Symbolic Approach with Reinforcement Learning for Explainable Question Answering in Pedestrian Anomaly Video Sequence.pdf)"
- Daiki Kimura, Stefan Zecevic, Subhajit Chaudhury, Sarathkrishna Swaminathan, Don Joven Agravante, Michiaki Tatsubori, Asim Munawar, and Alexander Gray, "Explainable Neuro-Symbolic Reinforcement Learning"
- Naman Shah, and Siddharth Srivastava, "Learning Neuro-Symbolic Abstractions for Motion Planning Under Uncertainty"
- Don Joven Agravante, Daiki Kimura, Michiaki Tatsubori, Asim Munawar, and Alexander Gray, "[Neuro-Symbolic Model-based RL with Logical Neural Network](assets/papers/Neuro-Symbolic Model-based RL with Logical Neural Network.pdf)"
- Leonid A Ugadiarov, and Aleksandr Panov, "[Object-Oriented Decomposition of World Model in Reinforcement Learning](assets/papers/Object-Oriented Decomposition of World Model in Reinforcement Learning.pdf)"

#### Poster

- Guy Azran, Mohamad H Danesh, Stefano V Albrecht, and Sarah Keren, "[Contextual Pre-Planning on Reward Machine Abstractions for Enhanced Transfer in Deep Reinforcement Learning](assets/papers/Contextual Pre-Planning on Reward Machine Abstractions for Enhanced Transfer in Deep Reinforcement Learning.pdf)"
- Zahra Chaghazardi, Saber Fallah, and Alireza Nezhad-Tamaddoni, "Explainable and Trustworthy Traffic Sign Detection for Safe Autonomous Driving: A Neuro-Symbolic approach"
- Giacomo Frisoni, Paolo Italiani, Stefano Salvatori, and Gianluca Moro, "Cogito Ergo Summ: Abstractive Summarization of Biomedical Papers via Semantic Parsing Graphs and Consistency Rewards"
- Chitra K Subramanian, Sarathkrishna Swaminathan, Miao Liu, Mauricio Longinos, Aporva Amarnath, Karthik Swaminathan, Martin Cochet, Kevin Roman, and Pradip Bose, "[A Neuro-Symbolic Approach to Runtime Optimization in Resource Constrained Heterogeneous Systems](assets/papers/A Neuro-Symbolic Approach to Runtime Optimization in Resource Constrained Heterogeneous Systems.pdf)"
- Daniil Kirilenko, Vitaliy Vorobyov, Alexey K Kovalev, and Aleksandr Panov, "[COMPAS: Compose Actions and Slots in Object-Centric World Models](assets/papers/COMPAS Compose Actions and Slots in Object-Centric World Models.pdf)"

{: #schedule }

# Schedule

| Time  | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Agenda&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Contents                                                                                                                                                                                         |
| ----- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 8:50  | Opening                                                                                                |                                                                                                                                                                                                  |
| 9:00  | Invited talk                                                                                           | Alexander Gray, "TBA"                                                                                                                                                                            |
| 10:00 | Contributed talk <br> (2 x 30 mins)                                                                    | - Object-Oriented Decomposition of World Model in Reinforcement Learning <br> - Explainable Neuro-Symbolic Reinforcement Learning                                                                |
| 11:00 | Invited talk                                                                                           | Luc De Raedt, "How to Make Logics Neurosymbolic"                                                                                                                                                                              |
| 12:00 | Lunch                                                                                                  |                                                                                                                                                                                                  |
| 13:00 | Contributed talk <br> (2 x 30 mins)                                                                    | - Introducing Trial-and-Error Exploration to Avoid Critical Failure for Efficient Reinforcement Learning <br> - Learning Neuro-Symbolic Abstraction for Motion Planning Under Uncertainty        |
| 14:00 | Invited talk                                                                                           | Wang-Zhou Dai, "Towards Openworld Abductive Learning"                                                                                                                                                                             |
| 15:00 | Contributed talk <br> (2 x 30 mins)                                                                    | - Neuro-Symbolic Model-based RL with Logical Neural Network <br> - A Neuro-Symbolic Approach with Reinforcement Learning for Explainable Question Answering in Pedestrian Anomaly Video Sequence |
| 16:00 | Poster                                                                                                 | All contributed papers                                                                                                                                                                           |
| 17:00 | Closing                                                                                                |                                                                                                                                                                                                  |

{: #invited }

# Invited Talks

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

{: #pcs }

# Program Committee

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
