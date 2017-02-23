###Adv: Artificial Intelligence and Subfields Practical with Dr. Ming-Hwa Wang

##classic techniques

* symbolic, rule based or algo based : emphasies use of prior knowledge, a system w/ manually created rules has limited success

* always have exceptions for rules
almost all AI problems are NP-hard O(2 to the N)
AI (ANN)

* reverse engineer the computational principles behind the brain and dublicate its functionality
(the 2nd best solution for every problem
early failure of AI

* Moore’s Law and parallel/distributed computing
*Use parallel compute processing to solve Moore’s Law problems, limits, speed

* bottom - input layer - then input linear regression 
* weight balancing
* feature extraction. 
* Deep learning as defined with more than 2 layers

* data mining - trying to locate something implied, not explicit

* inference - combined all facts together to come up with action plan

* function - combine 
* and/or

* predicate calculus - qualification 

* first order predicate calculus - function can call another function recursively)

* high level - prolog
you tell what you want, but now how to do it, they will do it for you

* think of like YC
* low lowel lang - 
* high level - C and java
* computer can only do one of them, try all possibilities

* Dempster-Shafter 
* sum is now 1
* Markov model 

* state machine - finite number of machine, # of transactions into other state, w/ some input data
finite state - fied number of state, you def finite.
10B finite 
* but after you say how many how many you want, if you want to say more than you want. infinite

* finite state => accept
otherwise
=> reject

* foliance (signal processing)

* RLL - punish if you are wrong, reward and punishment
sea world dolphin, dolphin give fish or not 

##Other references

* Keras slack and gitter channel based on CS231N 

* [Adam Getigey’s blog] 
(medium.com/@ageitgey)

* [Keras ex’s] : (https://github.com/fchollet/keras/blob/master/examples)

* [More than 3 layers visualized] (http://yosinski.com/deepvis)

* Why to use soft max - Udacity Machine Learning/Deep Learning Nanodegree (not Siraj, other guy) 

* Why to use rely
(Andrew - why to use relu in AI)
[https://web.stanford.edu/~awni/papers/relu_hybrid_icml2013_final.pdf]

* Open CV for open package and pre-processing

##classic feed forward NN
* flatten
* 28x27 - 784
* use float32 - in case ossciliation to 64 
* Keras  - legacy theano perspective, wrapper on top, model has to be compiled

* Number of calculations 
compute time is too much exponentially, 
so go to CNN instead of feed forward NN

* Max pool not avg pool
traditional ML - ensembling = good
In case of imgs, max pool works 
pooling operations 

* Filter sizes - power of 2
why selection, on CUDA (frameworks for 
Theano bc it uses CUDA underneath
If you use 32 may train faster, bc of underlying binary arithmetic
filters - depth dimension

* Transfer learning to use for tuning
remove top 2 layers (soft max layer and fully connected layer) 1000 classifications, then fine tune

* Max pooling - height, weight and width, doesn’t change depth dimension