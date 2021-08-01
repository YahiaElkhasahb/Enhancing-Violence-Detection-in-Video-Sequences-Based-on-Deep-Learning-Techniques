# Enhancing Violence Detection in Video Sequences Based on Deep Learning Techniques 
The method consists of extracting a set of frames belonging to the video, sending them to a pre-trained network called Descent, obtaining the output of one of its final layers, and from these outputs train another network architecture with a type of special neurons called LSTM. These neurons have memory and can analyze the temporal information of the video, if, at any time they detect violence, it will be classified as a violent video.
# System architecture Diagram (DenseNet)
![image](https://user-images.githubusercontent.com/46698452/125191406-9296b000-e242-11eb-81ad-cb7353400c65.png)
# Datasets used in this project
### Hockey Fight Dataset:
Hockey Fights is a dataset to introduce videos created to present fights and demonstrate that the proposed approach can reliably detect violence in sports footage, even in the presence of camera motion.
Specifically for evaluating violence detection systems, where both normal and violent activities occur in similar, dynamic settings, 
To this end, collected 1000 clips of action from hockey games of the National Hockey League (NHL), Each clip consists of 50 frames of 720×576 pixels and is manually labeled as “violent” or “non-violent”.
 -  Dataset on kaggle:https://www.kaggle.com/yassershrief/hockey-fight-vidoes
### RLVS Dataset:
RLVS “Real Life Violence Situations”, displays a group of video clips divided into video clips that collected from YouTube videos shows violence and non-violence in different situations and places Dataset Contains 2000 videos of full length 3 hours decided into 1000 videos of (Violence action) contained videos of bare hands fights, non-projectile weapon abuse fights that are sticks, knives, and big throw-able objects. Generally, the fights are near-distance fights. and 1000 videos of( non-violence action) Contained videos of shaking hands with friends, talking in a café, riding a horse, eating, taking a walk in the park, etc.
 -  Dataset on kaggle:https://www.kaggle.com/mohamedmustafa/real-life-violence-situations-dataset

## USED TOOLS 
 - Python3
 - TensorFlow
 - Opencv
 - Keras
 - matplotlib.pyplot
 - confusion_matrix
 - Numpy
 - google.colab files
 - kaggle
 
 ## SYSTEM RESULTS AND ITS PERFORMANCE
 We worked on different types of models using the same dataset (Hockey Fights, RLVS) 
 - DenseNet model 
    it's our proposed model that gets the best accuracy of the model of our experiments
    - on Hockey Fights Dataset get accuracy of  96.40 % and loss of  3.50%
    # ![Densenet-acc](https://user-images.githubusercontent.com/46698452/125192262-34200080-e247-11eb-8cb7-74f4a5ff3d6e.png)
    # ![Densenet-loss](https://user-images.githubusercontent.com/46698452/125192597-f3c18200-e248-11eb-923c-26c1cde790dd.png)
     - on RLVS Dataset get accuracy of  92.05%  and loss of  7.37%
    # ![__Densenet-acc](https://user-images.githubusercontent.com/46698452/125192750-b4dffc00-e249-11eb-9dc5-d09e0cc8ff41.png)
    # ![__Densenet-loss](https://user-images.githubusercontent.com/46698452/125192772-c75a3580-e249-11eb-9fe1-a47d058e924d.png)
 
 ## Our experiments using different models 
 Our experiences during the period of work on this project were based on a number of attempts to work on different models, and the results were as follows
 - on Hockey Fights Dataset :
 # ![image](https://user-images.githubusercontent.com/46698452/125193156-574caf00-e24b-11eb-938a-d33ffd9d91c4.png)
 # ![image](https://user-images.githubusercontent.com/46698452/125193221-9ed33b00-e24b-11eb-8bba-e7fe091ea42a.png)
 # ![image](https://user-images.githubusercontent.com/46698452/125193250-c62a0800-e24b-11eb-8aa7-7988491a2338.png)
 
 - on RLVS Dataset :
 # ![image](https://user-images.githubusercontent.com/46698452/125193276-ebb71180-e24b-11eb-8678-e09679b64280.png)
    
