# Computer Vision based Virtual Mouse for hands free computer interaction

- Developed a cutting-edge, computer vision-based virtual mouse system, enabling hands-free computer interaction for individuals with limited or no hand mobility, resulting in enhanced accessibility and independence.

- The proposed project aims to develop a hands-free computer interaction system, specifically a computer vision-based virtual mouse, that can be controlled using head movements. The system is intended to improve accessibility for individuals with limited or no use of their hands, such as those with spinal cord injuries or neuromuscular disorders. The virtual mouse will track the movement of the user's head and convert it into mouse movements on the screen. The project has the potential to enhance user experience in gaming or virtual reality applications where hands-free interaction is desirable. The development of a real-world system based on similar principles brings us one step closer to realising the fictional technology depicted in popular culture. The project requires the development of a robust computer vision algorithm, integration of the virtual mouse system with existing operating systems and software applications, and implementation of a user-friendly interface for configuring and calibrating the system to suit individual user needs. The system has the potential to increase independence and improve the quality of life for individuals with disabilities.

-  TECH STACK – HTML, CSS, JAVASCRIPT, BOOTSTRAP, PYTHON

## Working Actions

Open wide eyes + Mouth Open ==> Left Click

minimize eye + Mouth open ==> Right Click

move your eye sight to move the mouse

Video Explanation



## Authors
### Vishnu Rathod




## Deployment

To deploy this project run

```bash
  python run
```


# Hi, I'm Akash! 👋


## Lessons Learned
It was my Second hackathon. The Problem statement was so interesting that i was stuck to the computer screen straight 24 hrs, No Sleep, No distraction, complete focus...

Key Learnings

    - How the face and other objects are recognized with Mesh Detector

    - We started with 4 members but and at last i was alone left Key learning don't be afraid for errors

    - Always create a separate virtual environment (Very Important)

    - Installing few libraries may be challenging
        - Example Mediapipe requires python 10.5+(62 Bit) where as Autopy works on Python 8.0.0 only it was so hard to find out this later had to choose alternate of Autopy 

    - One of the most important thing I realised is to learn and execute always from command prompt (Importance of Linux)

What challenges did you face and how did you overcome them?

So as mentioned earlier I was constantly getting No Module Error inspite of successfully installing 
    steps to check if you face the same 
    - Always create venv

    - Check if the librari supports current python version

    - Few times you may have installed correct version but wrong bit (i.e.. 32 bit instead of 62 bit)

    - Try to find alternate libraries also 


## Installation

```bash
1. virtual environment
        python -m venv myenv

2. Install requirements from text file
        pip install -r requirements.txt
```
    
## Roadmap

- First
    Use mediapipe and try to locate the mesh for your face

- Second
    After locating the coordinates of eye lids try to find out the ratios of the eye as ratio will be consistent 

- Third 
    Once you have located the movement connect it with mouse with the help of pyautogui

- Fourth 
    Create a front end page for user interaction

- Fifth 
    With the help of Flask connect webpage and the backend


