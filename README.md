### **Snake** app based on *Tkinter* 
#### Hello, there! This is my first **Snake** app, which I built with python **OOP** conception. You will see all descriptions below.

<svg xmlns="http://www.w3.org/2000/svg" 
xmlns:xlink="http://www.w3.org/1999/xlink" 
width="88" height="20" role="img" 
aria-label="python: 3.7.4"><title>python: 3.7.4</title>
<linearGradient id="s" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/>
<stop offset="1" stop-opacity=".1"/></linearGradient><clipPath id="r">
<rect width="88" height="20" rx="3" fill="#fff"/></clipPath><g clip-path="url(#r)">
<rect width="49" height="20" fill="#555"/><rect x="49" width="39" height="20" fill="#e05d44"/>
<rect width="88" height="20" fill="url(#s)"/></g>
<g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110">
<text aria-hidden="true" x="255" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="390">python</text>
<text x="255" y="140" transform="scale(.1)" fill="#fff" textLength="390">python</text>
<text aria-hidden="true" x="675" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="290">3.7.4</text>
<text x="675" y="140" transform="scale(.1)" fill="#fff" textLength="290">3.7.4</text>
</g></svg>
<svg xmlns="http://www.w3.org/2000/svg" 
xmlns:xlink="http://www.w3.org/1999/xlink" 
width="80" height="20" role="img" 
aria-label="pillow: 8.0.1"><title>pillow: 8.0.1</title>
<linearGradient id="s" x2="0" y2="100%">
<stop offset="0" stop-color="#bbb" stop-opacity=".1"/>
<stop offset="1" stop-opacity=".1"/></linearGradient>
<clipPath id="r"><rect width="80" height="20" rx="3" fill="#fff"/></clipPath>
<g clip-path="url(#r)"><rect width="41" height="20" fill="#555"/><rect x="41" width="39" height="20" fill="#97ca00"/>
<rect width="80" height="20" fill="url(#s)"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110">
<text aria-hidden="true" x="215" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="310">pillow</text><text x="215" y="140" transform="scale(.1)" fill="#fff" textLength="310">pillow</text>
<text aria-hidden="true" x="595" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="290">8.0.1</text><text x="595" y="140" transform="scale(.1)" fill="#fff" textLength="290">8.0.1</text>
</g></svg> 

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

`git pull`
```
$ git init
$ git status
$ git add .
$ git commit -m 'My first app pushing to Github'
$ git remote add origin https://github.com/beckmiller/snake-game.git
$ git push -u origin master
```
>**That's all thank you for your attention!**
