# dot Getting Started - Using move forward and move backward blocks

## Introduction  @showdialog

Welcome! We need to light up LED in front of home position and LED behind the home position.  Like the following   

![image](https://user-images.githubusercontent.com/30203079/138978506-3fb5cd26-5ceb-443a-ae9d-897087ba8541.png)

## Step 1  

Drag and place the ``||dot:move forward||`` block in the ``||basic:on start||``.

```blocks
dot.moveForward()
```

## Step 2  

Drag and place another ``||dot:move backward||`` block in the ``||basic:on start||``.

```blocks
dot.moveForward()
dot.moveBackward()
```

## Step 3 

Drag and place another ``||dot:move backward||`` block in the ``||basic:on start||``.

```blocks
dot.moveForward()
dot.moveBackward()
dot.moveBackward()
```

## Step 4

Click ``|Download|`` to transfer your code to your micro:bit!

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
