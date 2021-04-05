# Assignement 1

## How does it work ? 💻


Follow this link :link: 

https://arcane-spire-64979.herokuapp.com/

You will find an extra button on the right side. This button will display your current drawing into a new window  :frame_photo:
Thus, you'll be able to download it as a png image :arrow_down: 

I know you are testing our projects on Chrome, unfortunately, I cannot explain why, this seems not to work on Chrome :sob: 
The image is displayed but cannot be save by right clicking on it. You will need first to open it again in an other window...

On my Mozilla it works perfectly, and after a lot of attempts, I still cannot figure out why it doesn't work on Chrome :worried: 


## What did I do ? ✍️


Using the canvas.toDataURL method() we can access a link reference of the current canvas whiteboard.
After opening a new blank window, we only need to add a <img/> with the link.
Putting everything in a function, itself called on a button onClick method and that's it !


## Do you want to try ? ☑️


If you want to run it on your own machine, download the zip file.📂

Run **```npm install```** to get all usefull packages :books:   

And then  **```node server.js```**

**PS : I have tried to implement your UI Tips, which, unfortunately ** **```event.keyCode```** **is now deprecated**
