# dot Getting Started - Using turn left and turn right blocks

## turn blocks @showdialog

### turn left block
We use turn left block, to set the direction of **dot** for the next step

![image](https://user-images.githubusercontent.com/30203079/138979074-c365f0b0-62fb-4f2e-8052-07a179c344f8.png)

### turn right block
We use turn right block, to set the direction of **dot** for the next step

![image](https://user-images.githubusercontent.com/30203079/138980986-3d5e8c0d-3e80-48dd-a543-1a3c1b1d5d23.png)

## Introduction  @showdialog

Welcome! We need to light up LED to the left of home position and LED to the right of the home position.  Like the following  

![image](https://user-images.githubusercontent.com/30203079/138978826-5b062da1-a618-446b-a0ef-3ef6d4d1e55f.png)

## Step 1  

Drag and place the ``||dot:turn left ||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
```

## Step 2  

Drag and place another ``||dot:move forward||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
dot.moveForward()
```

## Step 3 

Drag and place another ``||dot:turn right||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
dot.moveForward()
dot.turnRight()
```

## Step 4

Drag and place another ``||dot:turn right||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
dot.moveForward()
dot.turnRight()
dot.turnRight()
```

## Step 5

Drag and place another ``||dot:move forward||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
dot.moveForward()
dot.turnRight()
dot.turnRight(
dot.moveForward()
```
## Step 6

Drag and place another ``||dot:move forward||`` block in the ``||basic:on start||``.

```blocks
dot.turnLeft()
dot.moveForward()
dot.turnRight()
dot.turnRight(
dot.moveForward()
dot.moveForward()
```

## Step 7

Click ``|Download|`` to transfer your code to your micro:bit!

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
