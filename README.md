# Chrome-Dino-Reinforcement-Learning

NOTE: This repo is the basic implementation with few limitations. 



A Deep Convolutional Neural Network to play Google Chrome's offline Dino Run game by learning action patterns from visual input using a model-less Reinforcement Learning Algorithm

<string>NOTE:</strong> This is a basic-implementation repository with some limitations. Please refer https://github.com/Paperspace/DinoRunTutorial where I've used a GPU VM for better results, with scores upto 4000


<p>Refer the jupyter notebook for detailed implementation :<br>
https://github.com/govoyager/AI_DINO_GAME/blob/main/Reinforcement%20Learning%20Dino%20Run.ipynb

# Installation 
Start by cloning the repository
<br>
  AI DINO game
<br>
  

`Dependencies can be installed using pip install or conda install for Anaconda environment`<br><br>

<strong>Dependencies</strong>
- Python 3.6
- Selenium 
- OpenCV
- PIL
- Keras
- Chromium driver for Selenium

  
### Selenium 
  * pip install selenium
### OpenCV
  * python --version
  * pip -V
  * pip install opencv-python
### PIL
  1. Launch a command prompt if it isn't already open. To do so, open the Windows search bar, type cmd and click on the icon.
  2. Then, run the following command to download the get-pip.py file:
    - curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
### Chromium driver installation
ChromeDriver can be installed by going to (link - https://chromedriver.chromium.org/downloads) and also download the driver according to your chrome version which can be found under settings->About Chrome.
Change the path of chrome driver accordingly in Reinforcement Learning Dino Run.ipynb.(Default ="../chromedriver")
  
![gif](https://raw.githubusercontent.com/ravi72munde/Chrome-Dino-Reinforcement-Learning/master/img_data/trained_dino.gif)
<br/>

  
  ### References
  
  https://blog.paperspace.com/dino-run/
<br/>

