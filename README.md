## AI Based Automatic Movie Scene Cautioning System.
In a nutshell, this project is a simple human activity recognition model. The model is trained upon [**Kinetics dataset**](https://deepmind.com/research/open-source/kinetics) Dataset from DeepMind. The dataset consists of URL links to approximately 650,000 video clips that covers 700 human action classes.
Keeping scope of project in mind, we have restricted model inference for only four classes. The four classes are shown below:<br>
* smoking
* driving car
* riding a bike
* tasting beer

### 📰 Output:
![Video](https://github.com/snehitvaddi/Automatic-AI-Movie-Cautioning-System-/blob/master/fast-output.gif)

### 🛠 Implementation:
In file `Movie Cautioning System.ipynb`, you will have two implementations. One is **Frame-by-Frame** processing and the other is **Batch-wise processing**.<br>
A much better system could be implemented where the caution stays on frame for instead of flickering like in this case. 
