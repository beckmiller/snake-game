## **Snake** app based on *Tkinter* 
#### Hello, there! This is my first **Snake** app, which I built with python **OOP** conception. You will see all descriptions below.

![python](https://img.shields.io/badge/python-3.7.4-red)
![pillow](https://img.shields.io/badge/pillow-8.0.1-brightgreen)

1. First I installed virtual environment to my project

   ``` 
   python -m venv env 
   ```
   > Before start working I activated working env
2. Installed pillow library for working with images
   ```
   pip install pillow
   ``` 
3. Then I created `class Snake`, which I inherited from `Canvas` and made resizable main window
   ```python
   class Snake(tk.Canvas):
       pass
       ...

    #instance of Tk
    root = tk.Tk()
    #making resizable window
    root.resizable(False, False)
   ```
4. There are created 10 functions in the class include `__init__` method:
  
   Function name | Description
   --- |:---:
   *load_assets* |  Taking from assets img of food and snake 'png':   ![food](/assets/food.png) & ![snake](/assets/snake.png)
   *create_objects* | Creating food, snake objects and Score label
   *end_game* | Deleting all  objects from window and showing Game over and Score
   *...* | ....

5. Added `requirments.txt` and to `.gitignore` added `env` folder


   ```
   $ git init
   $ git status
   $ git add .
   $ git commit -m 'My first app pushing to Github'
   $ git remote add origin https://github.com/beckmiller/snake-game.git
   $ git push -u origin master
   ```
>**That's all thank you for your attention!**
