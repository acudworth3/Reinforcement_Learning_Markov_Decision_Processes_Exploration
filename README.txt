Andrew Cudworth
CS 7641 (Spring 2020)
Assignment 4 Markov Decision Processes 
https://www.omscs.gatech.edu/cs-7641-machine-learning

MDP Reinforcement Learning-analysis.pdf contains the analysis of learning models

Primary Topics:
-Markov Decision Processes
-Reinforcement Learning
-Value Iteration
-Policy Iteration 
-Q Learning
-Tower of Hanoi
-Grid Worlds

All files must be run with working directory set to src


FILES:
algos.py
    -contains QL,PI,and VI implimentations
    -called by training or plotting methods
analysis.py
    -contains a training object
    -train object can generate all plots and anlaysis
    

generic_script.py: 
"generic example of how to use algos+analysis"
    -examples of 
        -initiating MDPs
        -setting state space and parameters
        -all plot methods available
            plot_TOH_Policy_Length()
            plot_time_to_conv()
            plot_gamma_v_reward()
            plot_VI_analysis()
            plot_PI_analysis()
            plot_QL_gamma()
            plot_QL_alhpa()
            plot_QL_decay()
            plot_QL_epsilon()

Specific Scripts:
PI_Plot_gamma_script: Figures 6-8
QLearn_plot_alpha_script: Figures 12-14
QLearn_plot_decay_script: Figures 18-20
QLearn_plot_epsilon_script: Figures 15-17
QLearn_plot_gamma_script: Figures 9-11
QLearningscratch
Results_plot_script: Figures 21-22, 24-25
TOH_Plot_results: Figures 23
VI_Plot_gamma_script: Figures 3-5


heavily used references:
[4]	LearnDataSci, Brendan Martin Founder of. “Reinforcement Q-Learning from Scratch in Python with OpenAI Gym.” Learn Data Science - Tutorials, Books, Courses, and More, www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/.
[7]	Waqasqammar. “Waqasqammar/MDP-with-Value-Iteration-and-Policy-Iteration.” GitHub, 22 Sept. 2018, github.com/waqasqammar/MDP-with-Value-Iteration-and-Policy-Iteration/.
[8]	Xadahiya. “Xadahiya/Toh-Gym.” GitHub, github.com/xadahiya/toh-gym/blob/master/toh_gym/envs/toh_env.py.


PLAGARISM DISCLAIMER:
If you are currently enrolled in the class this assignment was written for and copy exploration methods, report contents, or hyperparameters
without attribution it is plagiarism. Additionally values in the reports and code have been modified to in a manner specific to this 
repo allowing easy detection of copying.
