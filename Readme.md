## Skin trouble detection



I thought up what it would be like if I can recognize about the rhythm or period of my skin or something. If I can know about the period, could I prevent that before it comes? Example, I can take medicine or care about taking ingredient in advance. 

So what if there was something to  check what kind of trouble it is, count and record it whenever I try.

So this program was started from the thought for AI team project. 



### function

**type of trouble**

* acne(papula-step1, pustula-step2)
* freckles
* darkcircles

My team used data of kaggle, AI hub for training YOLO v4-tiny model.



### Limit

* The boundary of skin trouble is not clear like a car, a person. So when marking, we made some standards like where to look as the boundary
* There weren't data that objects was visible clearly.  In photo, a couple of things was combined because of the attribute of trouble. So we couldn't divide clearly each.
* There wasn't lots of data about skin trouble not disease.
* It is not photo data of the entire face but pieces of face. So when testing for an entire face photo, there is some error.

