# A1: ML5 object classification

## Name

Lingfeng Li

## Link to your P5 submission

https://editor.p5js.org/billy1366/sketches/ZG2Cj9T4P

## What are you detecting, and what model did you use?

I'm using image classifiers trained with mobileNet. I'm detecting three objects: pen, water botles, and wallets. Or by changing the code to pre-trained mobileNet, it detects categories from imageNet. 


## How are you displaying the detected objects on the screen?  How did you improve on the example code that just outputs the label?

Through texts. It is better formatted.


## How does the user interact with your system? Do they know what it will detect? Do they push a button, make a face, or stand there?

Every 7 seconds, the webpage freezes, and ask the user if the prediction is correct. There is an internal counter that track the performance of the model and display the accuracy. The prediction tracking will require users to click correct/incorrect button in order for the system to countinue running. There is also a time count down so that users can better prepare for the prediction.

## Shoutouts

https://learn.ml5js.org/#/reference/image-classifier
https://p5js.org/reference/
https://www.youtube.com/watch?v=yNkAuWz5lnY&t=1240s
https://editor.p5js.org/galaxykate/sketches/qPqCtAATv


