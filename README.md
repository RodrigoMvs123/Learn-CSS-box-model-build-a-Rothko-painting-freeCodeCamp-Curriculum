# Learn-CSS-box-model-build-a-Rothko-painting-freeCodeCamp-Curriculum

https://www.youtube.com/watch?v=xyoo687froY  

https://raw.githubusercontent.com/RodrigoMvs123/Learn-CSS-box-model-build-a-Rothko-painting-freeCodeCamp-Curriculum/main/README.md

https://github.com/RodrigoMvs123/Learn-CSS-box-model-build-a-Rothko-painting-freeCodeCamp-Curriculum/blame/main/README.md

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
    </head>
    <body>
        <div className="canvas"></div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div className="canvas"></div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
}

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div className="frame"> 
            <div className="canvas"></div>
        </div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
}

.frame {
    border: solid black 50px;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div className="frame"> 
            <div className="canvas">
                <div class="one"></div>
            </div>
        </div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
    overflow: hidden;
}

.frame {
    border: solid black 50px;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}

.one {
    width: 425px;
    height: 150px;
    background-color: #efb762;
    margin: 20px auto;
}

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div className="frame"> 
            <div className="canvas">
                <div class="one"></div>
                <div class="two"></div>
            </div>
        </div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
    overflow: hidden;
}

.frame {
    border: solid black 50px;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}

.one {
    width: 425px;
    height: 150px;
    background-color: #efb762;
    margin: 20px auto;
}

.two {
    width: 475px;
    height: 200px;
    background-color: #8f0401;
    margin: auto;
}

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rothko Painting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div className="frame"> 
            <div className="canvas">
                <div class="one"></div>
                <div class="two"></div>
                <div class="three"></div> 
            </div>
        </div>
    </body>
</html>

Visual Studio Code
EXPLORER 
OPEN EDITORS 
css-rothko
index.html
styles.css

styles.css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
    overflow: hidden;
    filter: blur(2px);
}

.frame {
    border: solid black 50px;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}

.one {
    width: 425px;
    height: 150px;
    background-color: #efb762;
    margin: 20px auto;
    box-shadow: 0 0 3px 3px #efb762;  
    border-radius: 9px;
    transform: rotate(-0.6deg);
}

.two {
    width: 475px;
    height: 200px;
    background-color: #8f0401;
    margin: 0 auto 20px auto;
    box-shadow: 0 0 3px 3px #8f0401;  
    border-radius: 8px 10px 8px 10px;
    transform: rotate(0.4deg);
}

.three {
    width: 91%;
    height: 28%;
    background-color: #b20403;
    margin: auto;
    filter: blur(2px);
    box-shadow: 0 0 5px 5px #b20403;  
    border-radius: 30px 25px 60px 12px;
    transform: rotate(-0.2deg);
}

.one, .two {
    filter: blur(1px);
}

