#### Generate TV Scripts
##### Introduction
In this project, you'll generate your own Seinfeld TV scripts using RNNs. 
You'll be using a Seinfeld dataset of scripts from 9 seasons. 
The Neural Network you'll build will generate a new, "fake" TV script.

Getting the project files
The project files can be found in Udacity public GitHub repo, 
in the project-tv-script-generation folder. 
You can download the files from there, but it's better to clone the repository to your computer using:

```
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
```

#### Suggestions to Make Your Project Stand Out!
- Use validation data to choose the best model
- Initialize your model weights, especially the weights of the embedded layer to encourage model convergence
- Use topk sampling to generate new words
- Check out the "Advanced projects" section in the project overview to take this work even further!