#### Just a guy who get fun with playing with data and models.

```python
class MachineLearningEngineer:
    def __init__(self):
        self.name = "Akilesh A S"
        self.entertainment = "Ricing my Arch Linux"
        self.interests = ["Machine Learning", "Deep Learning", "Computer Vision", \
                          "Natural Language Processing", "Reinforcement Learning"]
        self.tools = ["Python", "Tensorflow", "Keras", "Scikit-learn", "Pandas", "Numpy", \
                      "Matplotlib", "Seaborn", "Plotly", "OpenCV", "NLTK", "Spacy", \
                      "Gensim", "Pytorch", "Fastai"]
        self.current_phase = "Learning and Exploring"
        self.email = "akilesh.ml.engineer@gmail.com"

    def say_hello(self):
        print(f"Hello, I'm {self.name} and I'm a Machine Learning Engineer.")
        print(f"When I'm not working, I'm busy {self.entertainment}.")
        print(f"I'm interested in {', '.join(self.interests)}")
        print(f"I'm familiar with {', '.join(self.tools)}")
        print(f"I'm currently in the phase of {self.current_phase}")
        print(f"Feel free to reach me at {self.email}")

me = MachineLearningEngineer()
me.say_hello()
```
