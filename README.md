 added justify-content: center

The Trial card text and icon were not level with the other cards. I think this is because the other two had 2 lines of text when this one only had one line. Adding justify-content made them all look relatively level with each other.

<br>
I set for cardDescription:

-  flex-direction
-  flex-basis
-  flex-grow

All as inherit because they all had the same value as card. 

<br>
As far as flex-basis goes for the card description 
I could not see any changes when I either had it on or took it off nor when I switched it to any other keyword everything stayed the same. I think this is because flex-basis deals with the dynamic sizing or responsive sizing. It basically says what the initial size of the box is before growing.(my understanding) 

# assessment-flexbox-cards
Starter code for flexbox cards assessment
