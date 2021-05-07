<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Rush for doorstep delivery or relax

Final project for the Building AI course

## Summary

e-commerce is booming and so are the deliveries to my doorstep.
I want to use image recognition to detect a delivery and change the sound of the doorbell in that case, so I'm notified ahead to rush to the door or just relax.


## Background

In general, the delivery personel has not much time and they need to know if I'm home and, when needed, sign for acceptance.
As I'm currently working from home at the attic, I have to rush down 2 floors to the door to get my delivery.
If a neighbour or friend or anybody else is ringing the bell, I want just go to the door relaxed (they have more time to wait).

It would be nice if we can train the algorithm to detect a delivery BEFORE the doorbell was rung.
Eg. truck arriving or delivery personel stepping up the driveway = predictor


## How is it used?

Users are my family and me.
The Ring doorbell will use a different chyme when delivery is deteced.


## Data sources and AI methods

My Ring video doorbell can be used to capture images and video of deliveries and train the model.
The same doorbell can be used to capture current persons coming to or waiting at the door.

## Challenges

* Detect small vs big packages. Eg. a postman with a registered letter or customs declaration payment.
* Friends & family carying packages will give false positives.
* Delivery personel that stops caring if somebody's home and just drops the delivery (already happening).
* API is needed to adjust Ring chime upon delivery


## What next?

We could adapt the system to turn on the sprinklers if unwanted visitor (insert examples here ;)) would ring the bell.


## Acknowledgments

* The last idea in "What's next?" is an adapted version of the cat & sprinkler example from this (or another) course
