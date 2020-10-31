This work is aimed at automatically tuning a pre-trained CNN layers with the knowledge of target dataset for improved transfer learning. 
![Overview of the proposed method. a) Typically, the CNN models used for transferring the knowledge are initially trained over a large-scale image dataset. b) Conventionally, while transferring the learned knowledge from the source task to the target task, the last one or a few layers of the pre-trained CNN are fine-tuned over the target dataset. c) The proposed AutoTune method tunes the $k$ number of layers automatically using Bayesian Optimization \cite{frazier2018tutorial}. Note that the lock and unlock symbols are used to represent the frozen and fine-tuned layers, respectively. Finally, the tuned CNN layers can be re-trained over the target dataset for improved transfer learning. Different colors represent different CNN layers.](Motivation_AutoTune1.png?raw=true "Title")
