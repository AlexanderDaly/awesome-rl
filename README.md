# Awesome Reinforcement Learning  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources dedicated to reinforcement learning.

We have pages for other topics: [awesome-rnn](https://github.com/kjw0612/awesome-rnn), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-random-forest](https://github.com/kjw0612/awesome-random-forest), [awesome-deep-rl](https://github.com/kengz/awesome-deep-rl)

Maintainers: [Hyunsoo Kim](http://sites.duke.edu/hyunsookim/), [Jiwon Kim](http://github.com/kjw0612)

We are looking for more contributors and maintainers!


## Contributing
Please feel free to [pull requests](https://github.com/aikorea/awesome-rl/pulls)

## Table of Contents

 - [Codes](#codes)
 - [Theory](#theory)
   - [Lectures](#lectures)
   - [Books](#books)
   - [Surveys](#surveys)
   - [Papers / Thesis](#papers--thesis)
 - [RLHF and LLM Alignment](#rlhf-and-llm-alignment)
 - [Offline Reinforcement Learning](#offline-reinforcement-learning)
 - [Applications](#applications)
   - [Game Playing](#game-playing)
   - [Robotics](#robotics)
   - [Control](#control)
   - [Operations Research](#operations-research)
   - [Human Computer Interaction](#human-computer-interaction)
 - [Tutorials / Websites](#tutorials--websites)
 - [Online Demos](#online-demos)
 - [Open Source Reinforcement Learning Platforms](#open-source-reinforcement-learning-platforms)

## Codes

### Classic and Educational
 - Codes for examples and exercises in Richard Sutton and Andrew Barto's Reinforcement Learning: An Introduction
  - [Python Code](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
  - [MATLAB Code](http://waxworksmath.com/Authors/N_Z/Sutton/sutton.html)
  - [C/Lisp Code](https://webdocs.cs.ualberta.ca/~sutton/book/code/code.html)
  - [Book](http://incompleteideas.net/book/the-book-2nd.html)
 - Simulation code for Reinforcement Learning Control Problems
  - [Pole-Cart Problem](http://pages.cs.wisc.edu/~finton/poledriver.html)
  - [Q-learning Controller](http://pages.cs.wisc.edu/~finton/qcontroller.html)
 - [MATLAB Environment and GUI for Reinforcement Learning](http://www.cs.colostate.edu/~anderson/res/rl/matlabpaper/rl.html)
 - [Reinforcement Learning Repository - University of Massachusetts, Amherst](http://www-anw.cs.umass.edu/rlr/)
 - [Brown-UMBC Reinforcement Learning and Planning Library (Java)](http://burlap.cs.brown.edu/)
 - [Reinforcement Learning in R (MDP, Value Iteration)](http://www.moneyscience.com/pg/blog/StatAlgo/read/635759/reinforcement-learning-in-r-markov-decision-process-mdp-and-value-iteration)
 - [Reinforcement Learning Environment in Python and MATLAB](https://jamh-web.appspot.com/download.htm)
 - [RL-Glue](http://glue.rl-community.org/wiki/Main_Page) (standard interface for RL) and [RL-Glue Library](http://library.rl-community.org/wiki/Main_Page)
 - [PyBrain Library](http://www.pybrain.org/) - Python-Based Reinforcement learning, Artificial intelligence, and Neural network
 - [RLPy Framework](http://rlpy.readthedocs.org/en/latest/) -  Value-Function-Based Reinforcement Learning Framework for Education and Research
 - [Maja](http://mmlf.sourceforge.net/) - Machine learning framework for problems in Reinforcement Learning in python
 - [TeachingBox](http://servicerobotik.hs-weingarten.de/en/teachingbox.php) - Java based Reinforcement Learning framework
 - [Policy Gradient Reinforcement Learning Toolbox for MATLAB](http://www.ias.informatik.tu-darmstadt.de/Research/PolicyGradientToolbox)
 - [PIQLE](http://sourceforge.net/projects/piqle/) - Platform Implementing Q-Learning and other RL algorithms
 - [BeliefBox](https://code.google.com/p/beliefbox/) - Bayesian reinforcement learning library and toolkit

### Deep RL Implementations
 - [Deep Q-Learning with Tensor Flow](https://github.com/nivwusquorum/tensorflow-deepq) - A deep Q learning demonstration using Google Tensorflow
 - [Atari](https://github.com/Kaixhin/Atari) - Deep Q-networks and asynchronous agents in Torch
 - [AgentNet](https://github.com/yandexdataschool/AgentNet) - A python library for deep reinforcement learning and custom recurrent networks using Theano+Lasagne.
 - [Reinforcement Learning Examples by RLCode](https://github.com/rlcode/reinforcement-learning) - A Collection of minimal and clean reinforcement learning examples
 - [PyTorch Deep RL](https://github.com/ShangtongZhang/DeepRL) - Popular deep RL algorithm implementations with PyTorch
 - [Black-DROPS](https://github.com/resibots/blackdrops) - Modular and generic code for the model-based policy search Black-DROPS algorithm (IROS 2017 paper) and easy integration with the [DART](http://dartsim.github.io/) simulator

### Modern Libraries (2020–2026)
 - [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) - Reliable PyTorch implementations of PPO, SAC, TD3, DQN, A2C, and more; the de facto standard for classic deep RL
 - [RL Baselines3 Zoo](https://github.com/DLR-RM/rl-baselines3-zoo) - Training framework, tuned hyperparameters, and pretrained agents for SB3
 - [Stable-Baselines3 Contrib](https://github.com/Stable-Baselines-Team/stable-baselines3-contrib) - Experimental algorithms (TQC, QR-DQN, Maskable PPO, etc.)
 - [CleanRL](https://github.com/vwxyzjn/cleanrl) - Single-file, research-friendly implementations of deep RL algorithms
 - [TorchRL](https://github.com/pytorch/rl) - Modular PyTorch-native RL library with vectorized environments and collectors
 - [Tianshou](https://github.com/thu-ml/tianshou) - Fast, pure-PyTorch RL platform with strong vectorized environment support
 - [Ray RLlib](https://docs.ray.io/en/latest/rllib/index.html) - Scalable distributed RL for single- and multi-agent training
 - [d3rlpy](https://github.com/takuseno/d3rlpy) - Offline deep RL library with CQL, IQL, Decision Transformer, and more
 - [garage](https://github.com/Farama-Foundation/Garage) - Reproducible RL research toolkit (successor to rlworkgroup/garage)
 - [RLkit](https://github.com/rail-berkeley/rlkit) - PyTorch RL framework from Berkeley RAIL, widely used in robotics research
 - [Softlearning](https://github.com/rail-berkeley/softlearning) - Maximum-entropy RL (SAC) framework from Berkeley RAIL
 - [skrl](https://github.com/Toni-SM/skrl) - Modular RL library (PyTorch and JAX) with Isaac Gym / Isaac Lab integration
 - [JAX RL](https://github.com/ikostrikov/jaxrl) - JAX implementations of SAC, DDPG, and related algorithms
 - [Brax](https://github.com/google/brax) - Differentiable physics engine and RL environments in JAX
 - [Acme](https://github.com/google-deepmind/acme) - DeepMind research framework for distributed RL
 - [Dopamine](https://github.com/google/dopamine) - Google research framework focused on reproducible RL baselines
 - [OpenRL](https://github.com/OpenRL-Lab/OpenRL) - General-purpose multi-agent RL research framework
 - [AgileRL](https://github.com/AgileRL/AgileRL) - Deep RL library with RLOps tooling for experiment management
 - [DI-engine](https://github.com/opendilab/DI-engine) - Generalized decision intelligence engine supporting many deep RL algorithms
 - [PPOxFamily](https://github.com/opendilab/PPOxFamily) - Tutorial course and code for understanding PPO and related methods

### RLHF and LLM Alignment Code
 - [TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl) - Hugging Face library for PPO, DPO, GRPO, and reward modeling
 - [verl](https://github.com/volcengine/verl) - Distributed RL training framework for LLM alignment (PPO, GRPO, agentic RL)
 - [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) - Open-source RLHF training with Ray, DeepSpeed, and vLLM
 - [DeepSpeed-Chat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat) - End-to-end RLHF pipeline with DeepSpeed
 - [Practical_RL](https://github.com/yandexdataschool/Practical_RL) - Course materials including policy gradient and RLHF basics

## Theory

### Lectures

#### Foundational
 - [UCL] [COMPM050/COMPGI13 Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) by David Silver
 - [UC Berkeley] CS188 Artificial Intelligence by Pieter Abbeel
   - [Lecture 8: Markov Decision Processes 1](https://www.youtube.com/watch?v=i0o-ui1N35U)
   - [Lecture 9: Markov Decision Processes 2](https://www.youtube.com/watch?v=Csiiv6WGzKM)
   - [Lecture 10: Reinforcement Learning 1](https://www.youtube.com/watch?v=ifma8G7LegE)
   - [Lecture 11: Reinforcement Learning 2](https://www.youtube.com/watch?v=Si1_YTw960c)
 - [Udacity (Georgia Tech.)] [CS7642 Reinforcement Learning](https://classroom.udacity.com/courses/ud600)
 - [Stanford] [CS229 Machine Learning - Lecture 16: Reinforcement Learning](https://www.youtube.com/watch?v=RtxI449ZjSc&feature=relmfu) by Andrew Ng
 - [UC Berkeley] [Deep RL Bootcamp](https://sites.google.com/view/deep-rl-bootcamp/lectures)
 - [UC Berkeley] [CS294 Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/) by John Schulman and Pieter Abbeel
 - [CMU] [10703: Deep Reinforcement Learning and Control, Spring 2017](https://katefvision.github.io/)
 - [MIT] [6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/)
   - [Lecture 2: Deep Reinforcement Learning for Motion Planning](https://www.youtube.com/watch?v=QDzM8r3WgBw&list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)

#### Modern Courses (2018–2026)
 - [UC Berkeley] [CS285: Deep Reinforcement Learning, Decision Making, and Control](https://rail.eecs.berkeley.edu/deeprlcourse/) by Sergey Levine — regularly updated; covers imitation learning, model-based RL, offline RL, exploration, and LLM RL
 - [DeepMind x UCL] [Reinforcement Learning Lecture Series](https://www.deepmind.com/learning-resources/reinforcement-learning-lecture-series-2021) by David Silver, Hado van Hasselt, and others
 - [Hugging Face] [Deep Reinforcement Learning Course](https://huggingface.co/learn/deep-rl-course/en/unit0/introduction) — hands-on course using Stable-Baselines3, CleanRL, and Gymnasium
 - [OpenAI] [Spinning Up in Deep RL](https://spinningup.openai.com/) — theory primer, algorithm taxonomy, and clean reference implementations (PPO, TRPO, SAC, TD3, DDPG)
 - [OpenAI] [Spinning Up Key Papers](https://spinningup.openai.com/en/latest/spinningup/keypapers.html) — curated reading list organized by topic
 - [CMU] [10-703 Deep Reinforcement Learning and Control](https://cmudeeprl.github.io/403_website/) — covers deep RL, imitation learning, and robotics
 - [OpenDILab] [PPOxFamily Tutorial Course](https://github.com/opendilab/PPOxFamily) — visual, interactive introduction to policy optimization


### Books
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (1st Edition, 1998) [[Book]](http://incompleteideas.net/book/the-book.html) [[Code]](http://incompleteideas.net/book/code/code.html)
 - Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (2nd Edition, 2018) [[Book]](http://incompleteideas.net/book/the-book-2nd.html) [[Code]](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
 - Csaba Szepesvari, Algorithms for Reinforcement Learning [[Book]](http://www.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
 - David Poole and Alan Mackworth, Artificial Intelligence: Foundations of Computational Agents [[Book Chapter]](http://artint.info/html/ArtInt_262.html)
 - Dimitri P. Bertsekas and John N. Tsitsiklis, Neuro-Dynamic Programming [[Book (Amazon)]](http://www.amazon.com/Neuro-Dynamic-Programming-Optimization-Neural-Computation/dp/1886529108/ref=sr_1_3?s=books&ie=UTF8&qid=1442461075&sr=1-3&refinements=p_27%3AJohn+N.+Tsitsiklis+Dimitri+P.+Bertsekas) [[Summary]](http://www.mit.edu/~dimitrib/NDP_Encycl.pdf)
 - Mykel J. Kochenderfer, Decision Making Under Uncertainty: Theory and Application [[Book (Amazon)]](http://www.amazon.com/Decision-Making-Under-Uncertainty-Application/dp/0262029251/ref=sr_1_1?ie=UTF8&qid=1441126550&sr=8-1&keywords=kochenderfer&pebp=1441126551594&perid=1Y6RG2EGRD26659CJHH9)
 - Sergey Levine, A. Kumar, G. Tucker, and J. Fu, Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems [[ArXiv]](https://arxiv.org/abs/2005.01643)


### Surveys

#### Classic
 - Leslie Pack Kaelbling, Michael L. Littman, Andrew W. Moore, Reinforcement Learning: A Survey, JAIR, 1996. [[Paper]](https://www.jair.org/media/301/live-301-1562-jair.pdf)
 - S. S. Keerthi and B. Ravindran, A Tutorial Survey of Reinforcement Learning, Sadhana, 1994. [[Paper]](http://www.cse.iitm.ac.in/~ravi/papers/keerthi.rl-survey.pdf)
 - Matthew E. Taylor, Peter Stone, Transfer Learning for Reinforcement Learning Domains: A Survey, JMLR, 2009. [[Paper]](http://machinelearning.wustl.edu/mlpapers/paper_files/jmlr10_taylor09a.pdf)
 - Jens Kober, J. Andrew Bagnell, Jan Peters, Reinforcement Learning in Robotics, A Survey, IJRR, 2013. [[Paper]](http://www.ias.tu-darmstadt.de/uploads/Publications/Kober_IJRR_2013.pdf)
 - Michael L. Littman, "Reinforcement learning improves behaviour from evaluative feedback." Nature 521.7553 (2015): 445-451. [[Paper]](http://www.nature.com/nature/journal/v521/n7553/full/nature14540.html)
 - Marc P. Deisenroth, Gerhard Neumann, Jan Peter, A Survey on Policy Search for Robotics, Foundations and Trends in Robotics, 2014. [[Book]](https://spiral.imperial.ac.uk:8443/bitstream/10044/1/12051/7/fnt_corrected_2014-8-22.pdf)

#### Recent (2019–2026)
 - Sergey Levine et al., Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems, 2020. [[Paper]](https://arxiv.org/abs/2005.01643)
 - Christiano et al., A Survey of Reinforcement Learning from Human Feedback, 2024. [[Paper]](https://arxiv.org/abs/2312.14925)
 - Yang et al., Foundation Models for Decision Making: Problems, Methods, and Opportunities, 2023. [[Paper]](https://arxiv.org/abs/2303.04129)
 - Yang et al., A Survey on Robotics with Foundation Models: toward Embodied AI, 2024. [[Paper]](https://arxiv.org/abs/2402.02385)
 - Liu et al., Integrating Reinforcement Learning with Foundation Models for Autonomous Robotics, 2024. [[Paper]](https://arxiv.org/abs/2410.16411)
 - Agarwal et al., What Matters In On-Policy Reinforcement Learning? A Large-Scale Empirical Study, 2020. [[Paper]](https://arxiv.org/abs/2006.05990)


### Papers / Thesis
Foundational Papers
 - Marvin Minsky, Steps toward Artificial Intelligence, Proceedings of the IRE, 1961. [[Paper]](http://staffweb.worc.ac.uk/DrC/Courses%202010-11/Comp%203104/Tutor%20Inputs/Session%209%20Prep/Reading%20material/Minsky60steps.pdf) (discusses issues in RL such as the "credit assignment problem")
 - Ian H. Witten, An Adaptive Optimal Controller for Discrete-Time Markov Environments, Information and Control, 1977. [[Paper]](http://www.cs.waikato.ac.nz/~ihw/papers/77-IHW-AdaptiveController.pdf) (earliest publication on temporal-difference (TD) learning rule)
  
Methods
 - Dynamic Programming (DP):
   - Christopher J. C. H. Watkins, Learning from Delayed Rewards, Ph.D. Thesis, Cambridge University, 1989. [[Thesis]](https://www.cs.rhul.ac.uk/home/chrisw/new_thesis.pdf)
 - Monte Carlo:
   - Andrew Barto, Michael Duff, Monte Carlo Inversion and Reinforcement Learning, NIPS, 1994. [[Paper]](http://papers.nips.cc/paper/865-monte-carlo-matrix-inversion-and-reinforcement-learning.pdf)
   - Satinder P. Singh, Richard S. Sutton, Reinforcement Learning with Replacing Eligibility Traces, Machine Learning, 1996. [[Paper]](http://www-all.cs.umass.edu/pubs/1995_96/singh_s_ML96.pdf)
 - Temporal-Difference:
   - Richard S. Sutton, Learning to predict by the methods of temporal differences. Machine Learning 3: 9-44, 1988. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-88-with-erratum.pdf)
 - Q-Learning (Off-policy TD algorithm):
   - Chris Watkins, Learning from Delayed Rewards, Cambridge, 1989. [[Thesis]](http://www.cs.rhul.ac.uk/home/chrisw/thesis.html)
 - Sarsa (On-policy TD algorithm):
   - G.A. Rummery, M. Niranjan, On-line Q-learning using connectionist systems, Technical Report, Cambridge Univ., 1994. [[Report]](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0CDIQFjACahUKEwj2lMm5wZDIAhUHkg0KHa6kAVM&url=ftp%3A%2F%2Fmi.eng.cam.ac.uk%2Fpub%2Freports%2Fauto-pdf%2Frummery_tr166.pdf&usg=AFQjCNHz6IrgcaaO5lzC7t8oEIBY9epozg&sig2=sa-emPme1m5Jav7YmaXsNQ&cad=rja)
   - Richard S. Sutton, Generalization in Reinforcement Learning: Successful examples using sparse coding, NIPS, 1996. [[Paper]](http://webdocs.cs.ualberta.ca/~sutton/papers/sutton-96.pdf)
 - R-Learning (learning of relative values)
   - Andrew Schwartz, A Reinforcement Learning Method for Maximizing Undiscounted Rewards, ICML, 1993. [[Paper-Google Scholar]](https://scholar.google.com/scholar?q=reinforcement+learning+method+for+maximizing+undiscounted+rewards&hl=en&as_sdt=0&as_vis=1&oi=scholart&sa=X&ved=0CBsQgQMwAGoVChMIho6p_MOQyAIVwh0eCh3XWAwM)
 - Function Approximation methods (Least-Square Temporal Difference, Least-Square Policy Iteration)
   - Steven J. Bradtke, Andrew G. Barto, Linear Least-Squares Algorithms for Temporal Difference Learning, Machine Learning, 1996. [[Paper]](http://www-anw.cs.umass.edu/pubs/1995_96/bradtke_b_ML96.pdf)
   - Michail G. Lagoudakis, Ronald Parr, Model-Free Least Squares Policy Iteration, NIPS, 2001. [[Paper]](http://www.cs.duke.edu/research/AI/LSPI/nips01.pdf) [[Code]](http://www.cs.duke.edu/research/AI/LSPI/)
 - Policy Search / Policy Gradient
   - Richard Sutton, David McAllester, Satinder Singh, Yishay Mansour, Policy Gradient Methods for Reinforcement Learning with Function Approximation, NIPS, 1999. [[Paper]](http://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf)
   - Jan Peters, Sethu Vijayakumar, Stefan Schaal, Natural Actor-Critic, ECML, 2005. [[Paper]](https://homes.cs.washington.edu/~todorov/courses/amath579/reading/NaturalActorCritic.pdf)
   - Jens Kober, Jan Peters, Policy Search for Motor Primitives in Robotics, NIPS, 2009. [[Paper]](http://papers.nips.cc/paper/3545-policy-search-for-motor-primitives-in-robotics.pdf)
   - Jan Peters, Katharina Mulling, Yasemin Altun, Relative Entropy Policy Search, AAAI, 2010. [[Paper]](http://www.kyb.tue.mpg.de/fileadmin/user_upload/files/publications/attachments/AAAI-2010-Peters_6439%5b0%5d.pdf)
   - Freek Stulp, Olivier Sigaud, Path Integral Policy Improvement with Covariance Matrix Adaptation, ICML, 2012. [[Paper]](http://arxiv.org/pdf/1206.4621v1.pdf)
   - Nate Kohl, Peter Stone, Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion, ICRA, 2004. [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
   - Marc Deisenroth, Carl Rasmussen, PILCO: A Model-Based and Data-Efficient Approach to Policy Search, ICML, 2011. [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
   - Scott Kuindersma, Roderic Grupen, Andrew Barto, Learning Dynamic Arm Motions for Postural Recovery, Humanoids, 2011. [[Paper]](http://www-all.cs.umass.edu/pubs/2011/kuindersma_g_b_11.pdf)
   - Konstantinos Chatzilygeroudis, Roberto Rama, Rituraj Kaushik, Dorian Goepp, Vassilis Vassiliades, Jean-Baptiste Mouret, Black-Box Data-efficient Policy Search for Robotics, IROS, 2017. [[Paper](https://arxiv.org/abs/1703.07261)]
 - Hierarchical RL
   - Richard Sutton, Doina Precup, Satinder Singh, Between MDPs and Semi-MDPs: A Framework for Temporal Abstraction in Reinforcement Learning, Artificial Intelligence, 1999. [[Paper]](https://webdocs.cs.ualberta.ca/~sutton/papers/SPS-aij.pdf)
   - George Konidaris, Andrew Barto, Building Portable Options: Skill Transfer in Reinforcement Learning, IJCAI, 2007. [[Paper]](http://www-anw.cs.umass.edu/pubs/2007/konidaris_b_IJCAI07.pdf)
 - Deep Learning + Reinforcement Learning (A sample of recent works on DL+RL)
   - V. Mnih, et. al., Human-level Control through Deep Reinforcement Learning, Nature, 2015. [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D)
   - Xiaoxiao Guo, Satinder Singh, Honglak Lee, Richard Lewis, Xiaoshi Wang, Deep Learning for Real-Time Atari Game Play Using Offline Monte-Carlo Tree Search Planning, NIPS, 2014. [[Paper]](http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf)
   - Sergey Levine, Chelsea Finn, Trevor Darrel, Pieter Abbeel, End-to-End Training of Deep Visuomotor Policies. ArXiv, 16 Oct 2015. [[ArXiv]](http://arxiv.org/pdf/1504.00702v3.pdf)
   - Tom Schaul, John Quan, Ioannis Antonoglou, David Silver, Prioritized Experience Replay, ArXiv, 18 Nov 2015. [[ArXiv]](http://arxiv.org/pdf/1511.05952v2.pdf)
   - Hado van Hasselt, Arthur Guez, David Silver, Deep Reinforcement Learning with Double Q-Learning, ArXiv, 22 Sep 2015. [[ArXiv]](http://arxiv.org/abs/1509.06461)
   - Volodymyr Mnih, Adrià Puigdomènech Badia, Mehdi Mirza, Alex Graves, Timothy P. Lillicrap, Tim Harley, David Silver, Koray Kavukcuoglu, Asynchronous Methods for Deep Reinforcement Learning, ArXiv, 4 Feb 2016. [[ArXiv]](https://arxiv.org/abs/1602.01783)

Modern Deep RL (2016–2026)
 - John Schulman et al., Proximal Policy Optimization Algorithms, 2017. [[Paper]](https://arxiv.org/abs/1707.06347)
 - Timothy P. Lillicrap et al., Continuous Control with Deep Reinforcement Learning (DDPG), ICLR, 2016. [[Paper]](https://arxiv.org/abs/1509.02971)
 - Scott Fujimoto, Herke van Hoof, David Meger, Addressing Function Approximation Error in Actor-Critic Methods (TD3), ICML, 2018. [[Paper]](https://arxiv.org/abs/1802.09477)
 - Tuomas Haarnoja et al., Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning, ICML, 2018. [[Paper]](https://arxiv.org/abs/1801.01290)
 - Matteo Hessel et al., Rainbow: Combining Improvements in Deep Reinforcement Learning, AAAI, 2018. [[Paper]](https://arxiv.org/abs/1710.02298)
 - David Silver et al., Mastering the game of Go without human knowledge (AlphaGo Zero), Nature, 2017. [[Paper]](https://www.nature.com/articles/nature24270)
 - David Silver et al., A general reinforcement learning algorithm that masters chess, shogi, and Go through self-play (AlphaZero), Science, 2018. [[Paper]](https://arxiv.org/abs/1712.01815)
 - Julian Schrittwieser et al., Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero), Nature, 2020. [[Paper]](https://arxiv.org/abs/1911.08265)
 - Lili Chen et al., Decision Transformer: Reinforcement Learning via Sequence Modeling, NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2106.01345)
 - Sergey Levine et al., Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems, 2020. [[Paper]](https://arxiv.org/abs/2005.01643)
 - Scott Fujimoto, Shixiang Gu, Off-Policy Deep Reinforcement Learning without Importance Sampling (BCQ), ICML, 2019. [[Paper]](https://arxiv.org/abs/1812.02900)
 - Aviral Kumar et al., Conservative Q-Learning for Offline Reinforcement Learning (CQL), NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2006.04779)
 - Ilya Kostrikov, Ashvin Nair, Sergey Levine, Offline Reinforcement Learning with Implicit Q-Learning (IQL), ICLR, 2022. [[Paper]](https://arxiv.org/abs/2110.06169)
 - Cheng Chi et al., Diffusion Policy: Visuomotor Policy Learning via Action Diffusion, RSS, 2023. [[Paper]](https://arxiv.org/abs/2303.04137)
 - Alhussein Fawzi et al., Discovering faster matrix multiplication algorithms with reinforcement learning (AlphaTensor), Nature, 2022. [[Paper]](https://arxiv.org/abs/2210.01691)
 - DeepSeek-AI, DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, 2025. [[Paper]](https://arxiv.org/abs/2501.12948)


## RLHF and LLM Alignment

RLHF (Reinforcement Learning from Human Feedback) has become a central application of RL, especially for aligning large language models. Key algorithms and resources:

### Key Papers
 - Paul Christiano et al., Deep Reinforcement Learning from Human Preferences, NeurIPS, 2017. [[Paper]](https://arxiv.org/abs/1706.03741)
 - Long Ouyang et al., Training language models to follow instructions with human feedback (InstructGPT), NeurIPS, 2022. [[Paper]](https://arxiv.org/abs/2203.02155)
 - Rafael Rafailov et al., Direct Preference Optimization: Your Language Model is Secretly a Reward Model (DPO), NeurIPS, 2023. [[Paper]](https://arxiv.org/abs/2305.18290)
 - Zhihong Shao et al., DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models (GRPO), 2024. [[Paper]](https://arxiv.org/abs/2402.03300)
 - DeepSeek-AI, DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, 2025. [[Paper]](https://arxiv.org/abs/2501.12948)

### Surveys
 - Christiano et al., A Survey of Reinforcement Learning from Human Feedback, 2024. [[Paper]](https://arxiv.org/abs/2312.14925)

### Libraries and Frameworks
 - [TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl) — PPO, DPO, GRPO, reward modeling, and SFT
 - [verl](https://github.com/volcengine/verl) — Distributed RL training for LLM alignment at scale
 - [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) — Full RLHF pipeline with Ray and vLLM
 - [DeepSpeed-Chat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat) — Microsoft's RLHF reference implementation


## Offline Reinforcement Learning

Offline RL learns policies from fixed datasets without online environment interaction. Key benchmarks and resources:

### Benchmarks and Datasets
 - [D4RL](https://github.com/Farama-Foundation/D4RL) — Standard offline RL benchmark (MuJoCo, AntMaze, Adroit, etc.)
 - [RL Unplugged](https://github.com/google-deepmind/deepmind-research/tree/master/rl_unplugged) — DeepMind offline RL datasets
 - [RoboMimic](https://github.com/ARISE-Initiative/robomimic) — Large-scale robot manipulation demonstration datasets
 - [Minari](https://github.com/Farama-Foundation/Minari) — Standard format for offline RL datasets (successor to D4RL)

### Key Algorithms
 - BCQ (Fujimoto et al., 2019), CQL (Kumar et al., 2020), IQL (Kostrikov et al., 2022), Decision Transformer (Chen et al., 2021)

### Libraries
 - [d3rlpy](https://github.com/takuseno/d3rlpy) — Comprehensive offline RL library
 - [CORL](https://github.com/corl-team/CORL) — Clean, single-file offline RL implementations


## Applications
### Game Playing
Traditional Games
  - Backgammon - "TD-Gammon" game play using TD(λ) (Tesauro, ACM 1995) [[Paper]](http://www.bkgm.com/articles/tesauro/tdl.html)
  - Chess - "KnightCap" program using TD(λ) (Baxter, arXiv 1999) [[arXiv]](http://arxiv.org/pdf/cs/9901002v1.pdf)
  - Chess - Giraffe: Using deep reinforcement learning to play chess (Lai, arXiv 2015) [[arXiv]](http://arxiv.org/pdf/1509.01549v2.pdf)
  - Go/Chess/Shogi - AlphaZero: general RL algorithm mastering multiple board games through self-play (Silver et al., Science 2018) [[Paper]](https://arxiv.org/abs/1712.01815)
  - Matrix Multiplication - AlphaTensor: discovering faster matrix multiplication algorithms with RL (Fawzi et al., Nature 2022) [[Paper]](https://arxiv.org/abs/2210.01691)

Computer Games
  - Human-level Control through Deep Reinforcement Learning (Mnih, Nature 2015) [[Paper]](http://www.readcube.com/articles/10.1038%2Fnature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D) [[Code]](https://sites.google.com/a/deepmind.com/dqn/) [[Video]](https://www.youtube.com/watch?v=iqXKQf2BOSE)
  - Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero, Schrittwieser et al., Nature 2020) [[Paper]](https://arxiv.org/abs/1911.08265)
  - [OpenAI Five](https://openai.com/index/openai-five/) — Dota 2 agents trained with large-scale PPO
  - [Flappy Bird Reinforcement Learning](https://github.com/SarvagyaVaish/FlappyBirdRL) [[Video]](https://www.youtube.com/watch?v=xM62SpKAZHU)
  - MarI/O - learning to play Mario with evolutionary reinforcement learning using artificial neural networks (Stanley, Evolutionary Computation 2002) [[Paper]](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) [[Video]](https://www.youtube.com/watch?v=qv6UVOQ0F44)

### Robotics
  - Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion (Kohl, ICRA 2004) [[Paper]](http://www.cs.utexas.edu/~pstone/Papers/bib2html-links/icra04.pdf)
  - Robot Motor SKill Coordination with EM-based Reinforcement Learning (Kormushev, IROS 2010) [[Paper]](http://kormushev.com/papers/Kormushev-IROS2010.pdf) [[Video]](https://www.youtube.com/watch?v=W_gxLKSsSIE)
  - Generalized Model Learning for Reinforcement Learning on a Humanoid Robot (Hester, ICRA 2010) [[Paper]](https://ccc.inaoep.mx/~mdprl/documentos/Hester_2010.pdf) [[Video]](https://www.youtube.com/watch?v=mRpX9DFCdwI&list=PL5nBAYUyJTrM48dViibyi68urttMlUv7e&index=12)
  - Autonomous Skill Acquisition on a Mobile Manipulator (Konidaris, AAAI 2011) [[Paper]](http://lis.csail.mit.edu/pubs/konidaris-aaai11b.pdf) [[Video]](https://www.youtube.com/watch?v=yUICAkSQTZY)
  - PILCO: A Model-Based and Data-Efficient Approach to Policy Search (Deisenroth, ICML 2011) [[Paper]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf)
  - Incremental Semantically Grounded Learning from Demonstration (Niekum, RSS 2013) [[Paper]](http://people.cs.umass.edu/~sniekum/pubs/NiekumRSS2013.pdf)
  - Efficient Reinforcement Learning for Robots using Informative Simulated Priors (Cutler, ICRA 2015) [[Paper]](http://markjcutler.com/papers/Cutler15_ICRA.pdf) [[Video]](https://www.youtube.com/watch?v=kKClFx6l1HY)
  - Robots that can adapt like animals (Cully, Nature 2015) [[Paper](https://arxiv.org/abs/1407.3501)] [[Video](https://www.youtube.com/watch?v=T-c17RKh3uE)] [[Code](https://github.com/resibots/cully_2015_nature)]
  - Black-Box Data-efficient Policy Search for Robotics (Chatzilygeroudis, IROS 2017) [[Paper](https://arxiv.org/abs/1703.07261)] [[Video](https://www.youtube.com/watch?v=kTEyYiIFGPM)] [[Code](https://github.com/resibots/blackdrops)]
  - QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation (Kalashnikov et al., 2018) [[Paper]](https://arxiv.org/abs/1806.10293)
  - Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations (Rajeswaran et al., RSS 2018) [[Paper]](https://arxiv.org/abs/1709.10087)
  - Diffusion Policy: Visuomotor Policy Learning via Action Diffusion (Chi et al., RSS 2023) [[Paper]](https://arxiv.org/abs/2303.04137) [[Code]](https://github.com/real-stanford/diffusion_policy)
  - RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control (Brohan et al., 2023) [[Paper]](https://arxiv.org/abs/2307.15818)
  - Open X-Embodiment: Robotic Learning Datasets and RT-X Model (Padalkar et al., 2024) [[Paper]](https://arxiv.org/abs/2310.08864)


### Control
  - An Application of Reinforcement Learning to Aerobatic Helicopter Flight (Abbeel, NIPS 2006) [[Paper]](http://heli.stanford.edu/papers/nips06-aerobatichelicopter.pdf) [[Video]](https://www.youtube.com/watch?v=VCdxqn0fcnE)
  - Autonomous helicopter control using Reinforcement Learning Policy Search Methods (Bagnell, ICRA 2001) [[Paper]](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1082&context=robotics)

### Operations Research
  - Scaling Average-reward Reinforcement Learning for Product Delivery (Proper, AAAI 2004) [[Paper]](http://web.engr.oregonstate.edu/~proper/AAAI04SProper.pdf)
  - Cross Channel Optimized Marketing by Reinforcement Learning (Abe, KDD 2004) [[Paper]](http://www.research.ibm.com/people/n/nabe/kdd04AVAS.pdf)

### Human Computer Interaction
  - Optimizing Dialogue Management with Reinforcement Learning: Experiments with the NJFun System (Singh, JAIR 2002) [[Paper]](http://web.eecs.umich.edu/~baveja/Papers/RLDSjair.pdf)
  - Training language models to follow instructions with human feedback (InstructGPT, Ouyang et al., 2022) [[Paper]](https://arxiv.org/abs/2203.02155)


## Tutorials / Websites
  - Mance Harmon and Stephanie Harmon, [Reinforcement Learning: A Tutorial](http://old.nbu.bg/cogs/events/2000/Readings/Petrov/rltutorial.pdf)
  - C. Igel, M.A. Riedmiller, et al., Reinforcement Learning in a Nutshell, ESANN, 2007. [[Paper]](http://image.diku.dk/igel/paper/RLiaN.pdf)
  - UNSW - [Reinforcement Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/index.html)
   - [Introduction](http://www.cse.unsw.edu.au/~cs9417ml/RL1/introduction.html)
   - [TD-Learning](http://www.cse.unsw.edu.au/~cs9417ml/RL1/tdlearning.html)
   - [Q-Learning and SARSA](http://www.cse.unsw.edu.au/~cs9417ml/RL1/algorithms.html)
   - [Applet for "Cat and Mouse" Game](http://www.cse.unsw.edu.au/~cs9417ml/RL1/applet.html)
  - [ROS Reinforcement Learning Tutorial](http://wiki.ros.org/reinforcement_learning/Tutorials/Reinforcement%20Learning%20Tutorial)
  - [POMDP for Dummies](http://cs.brown.edu/research/ai/pomdp/tutorial/index.html)
  - Scholarpedia articles on:
   - [Reinforcement Learning](http://www.scholarpedia.org/article/Reinforcement_learning)
   - [Temporal Difference Learning](http://www.scholarpedia.org/article/Temporal_difference_learning)
  - Repository with useful [MATLAB Software, presentations, and demo videos](http://busoniu.net/repository.php)
  - [Bibliography on Reinforcement Learning](http://liinwww.ira.uka.de/bibliography/Neural/reinforcement.learning.html)
  - UC Berkeley - CS 294: Deep Reinforcement Learning, Fall 2015 (John Schulman, Pieter Abbeel) [[Class Website]](http://rll.berkeley.edu/deeprlcourse/)
  - [Blog posts on Reinforcement Learning, Parts 1-4](https://studywolf.wordpress.com/2012/11/25/reinforcement-learning-q-learning-and-exploration/) by Travis DeWolf
  - [The Arcade Learning Environment](http://www.arcadelearningenvironment.org/) - Atari 2600 games environment for developing AI agents
  - [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/) by Andrej Karpathy
  - [Demystifying Deep Reinforcement Learning](https://www.nervanasys.com/demystifying-deep-reinforcement-learning/) 
  - [Let's make a DQN](https://jaromiru.com/2016/09/27/lets-make-a-dqn-theory/) 
  - [Simple Reinforcement Learning with Tensorflow, Parts 0-8](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0#.78km20i8r) by Arthur Juliani
  - [Practical_RL](https://github.com/yandexdataschool/Practical_RL) - github-based course in reinforcement learning in the wild (lectures, coding labs, projects)
  - [OpenAI Spinning Up in Deep RL](https://spinningup.openai.com/) - theory, algorithm taxonomy, and reference implementations
  - [Hugging Face Deep RL Course](https://huggingface.co/learn/deep-rl-course/en/unit0/introduction) - interactive course with Colab notebooks
  - [Lil'Log: A (Long) Peek into Reinforcement Learning](https://lilianweng.github.io/posts/2018-02-19-rl-overview/) by Lilian Weng — comprehensive RL overview
  - [OpenRL Benchmark](https://github.com/openrlbenchmark/openrlbenchmark) — tracked experiment results across CleanRL, SB3, and other libraries


## Online Demos
 - [Real-world demonstrations of Reinforcement Learning](http://www.dcsc.tudelft.nl/~robotics/media.html)
 - [Deep Q-Learning Demo](http://cs.stanford.edu/people/karpathy/convnetjs/demo/rldemo.html) - A deep Q learning demonstration using ConvNetJS
 - [Deep Q-Learning with Tensor Flow](https://github.com/nivwusquorum/tensorflow-deepq) - A deep Q learning demonstration using Google Tensorflow
 - [Reinforcement Learning Demo](http://cs.stanford.edu/people/karpathy/reinforcejs/) - A reinforcement learning demo using reinforcejs by Andrej Karpathy


## Open Source Reinforcement Learning Platforms

### Environments
 - [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) - The maintained successor to OpenAI Gym; standard RL environment API
 - [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) - Multi-agent RL environments (successor to OpenAI's multi-agent envs)
 - [OpenAI gym](https://github.com/openai/gym) - Original toolkit (archived; use Gymnasium instead)
 - [MuJoCo](https://github.com/google-deepmind/mujoco) - Advanced physics simulation (now free and open source)
 - [MuJoCo Playground](https://github.com/google-deepmind/mujoco_playground) - GPU-accelerated RL environments built on MuJoCo MJX
 - [Brax](https://github.com/google/brax) - Differentiable physics engine with built-in RL environments in JAX
 - [DeepMind Control Suite](https://github.com/google-deepmind/dm_control) - Continuous control benchmark environments
 - [Meta-World](https://github.com/Farama-Foundation/Metaworld) - Multi-task robotic manipulation benchmark
 - [RLBench](https://github.com/stepjam/RLBench) - Large-scale robot learning benchmark with 100+ tasks
 - [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - NVIDIA GPU-accelerated robot learning framework (successor to Isaac Gym)
 - [ManiSkill](https://github.com/haosulab/ManiSkill) - GPU-parallelized robot manipulation simulation
 - [ALFWorld](https://github.com/alfworld/alfworld) - Interactive text and embodied environments for household tasks
 - [Procgen](https://github.com/openai/procgen) - Procedurally generated game-like environments for generalization research
 - [Minigrid](https://github.com/Farama-Foundation/Minigrid) - Simple, fast gridworld environments for RL research

### Training Platforms and Frameworks
 - [OpenAI gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms
 - [DeepMind Lab](https://github.com/deepmind/lab) - A customisable 3D platform for agent-based AI research
 - [Project Malmo](https://github.com/Microsoft/malmo) - A platform for Artificial Intelligence experimentation and research built on top of Minecraft by Microsoft
 - [ViZDoom](https://github.com/Marqt/ViZDoom) - Doom-based AI research platform for reinforcement learning from raw visual information
 - [Retro Learning Environment](https://github.com/nadavbh12/Retro-Learning-Environment) - An AI platform for reinforcement learning based on video game emulators. Currently supports SNES and Sega Genesis. Compatible with OpenAI gym.
 - [rllab](https://github.com/openai/rllab) - A framework for developing and evaluating reinforcement learning algorithms, fully compatible with OpenAI Gym (superseded by garage and RLlib)
 - [Ray RLlib](https://docs.ray.io/en/latest/rllib/index.html) - Scalable reinforcement learning library with multi-agent and distributed training support
 - [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) - Reliable PyTorch RL algorithm implementations
 - [TorchRL](https://github.com/pytorch/rl) - PyTorch-native modular RL library
 - [TensorForce](https://github.com/tensorforce/tensorforce) - A TensorFlow library for applied reinforcement learning.
 - [keras-rl](https://github.com/matthiasplappert/keras-rl) - State-of-the art deep reinforcement learning algorithms in Keras designed for compatibility with OpenAI.
 - [BURLAP](http://burlap.cs.brown.edu) - Brown-UMBC Reinforcement Learning and Planning, a library written in Java
 - [MAgent](https://github.com/geek-ai/MAgent) - A Platform for Many-agent Reinforcement Learning.
 - [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) - Unity engine toolkit for training agents in 3D environments
 - [DIAMBRA Arena](https://github.com/DIAMBRA-AI/diambra-arena) - Competitive fighting game environments for RL research
