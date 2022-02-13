# Y2K website 

**The COVID-19 pandemic is a major health crisis that has changed the life of millions globally.
In this global pandemic era, where everything has become "online", we have created a solution to reduce the mental stress and improve physical health of people.**

## Built With

* [DashaAI](https://dasha.ai/en-us)
* [Mediapipe](https://google.github.io/mediapipe/)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Python](https://docs.python.org/3/)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites
* Python should be installed

### Activate Virtual Environment

* . venv/bin/activate  **for Windows**
* venv\Scripts\activate **for MacOS**

### Installations

```bash
pip install flask
```

```bash
pip install mediapipe
```

### Run the program
```bash
$ flask run
  * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
### How does it work?
* User selects a yoga plan that fits their needs.
* User is taken to a webpage with all the details about the plan selected
*	User clicks on the pose of their preference
*	User logs in to their account to keep track of their progress
*	App provides instructions on how to execute the pose
*	Once ready, the user performs  the pose 
*	Video is automatically processed in real time using [OpenCV](https://github.com/opencv/opencv), an open-source, deep learning library which detects the keypoints using mediapipe.
*	Feedback is provided to the user on how they can safely improve their pose in real time

[Watch Demo Video](https://youtu.be/rJ501wact-o)
