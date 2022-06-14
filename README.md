# Editor Image Plugin
 Plugin for the Godot game engine that allows you to have an image background for your code editor. The image will keep it's aspect ratio and stay centered to your code editor regardless of it's size.


## To Change the Image
To change the image shown on your background, simply open up the addons folder and replace the Background.png file with another png of your choosing. Be sure to name it Background.png to be
recognized. Opacity will be handled by the code so no need to change this in your image. I use a png to allow the option to use images with transparent backgrounds which in my opinion provide the best results.


## Examples
<img src="images/demo1.png" >
<img src="images/demo1.5.png" >
<img src="images/demo2.png" >


## On Load
When you open a project you may notice an error in the output, this is from specific parts of the editor not being ready at the time of the plugin's initialization. Simply open up a script, of course you need a scene open, and save any script with a quick ctrl s.
