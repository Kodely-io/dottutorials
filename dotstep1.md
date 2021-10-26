# dot Getting Started - Learning to use move forward block

## Setup & Intro Videos @showdialog
dot introductory videos 

[Walk-thru setting up dot video](https://www.youtube.com/watch?v=1nse-mlKPsA)

[dot intro video](https://youtu.be/jNrXkMRNLGw)

## Move Forward block 
![image](https://user-images.githubusercontent.com/30203079/138968443-bd099a03-07e6-4541-9416-836f79523902.png)

We use move forward block, to move **dot** one step forward in the current direction

## Introduction @showdialog

Welcome! We need to move dot from home position to the third LED on first row. Like the following  

![image](https://user-images.githubusercontent.com/30203079/138969100-58474f95-6f0c-4d93-951e-f3ffb7883458.png)


## Step 1 

Drag and place the ``||dot:move forward||`` block in the ``||basic:on start||``.


```blocks
dot.moveForward()
```

## Step 2 

Drag and place another ``||dot:move forward||`` block in the ``||basic:on start||``.


```blocks
dot.moveForward()
dot.moveForward()
```

## Step 3 

Drag and place another ``||dot:move forward||`` block in the ``||basic:on start||``.


```blocks
dot.moveForward()
dot.moveForward()
dot.moveForward()
```

## Step 4

Click ``|Download|`` to transfer your code to your micro:bit!



<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
