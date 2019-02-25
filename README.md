# transcrypt-js-namespaces

# transcrypt do good job but

when you write   `document.getElementById("myelement")` your python linter  (pylint or other)   you tell undefine variable and don't suggesse you  `document` methods in js

# what is the solution ?

I suggess , like in this reposotory  , to make python interface for javascript object and methods 

I create folder named  interfaces , inside yhis folder I create  some class (like document,window, math ..), I import document in my code : hello.py given in transcrypt exemple,
and I solve the probleme : my python linter  recognize js document  and suggest/complete when editng in Visual Studio Code IDE  but transcrypt compiler skip interfaces import because
my import is like this :
`
#__pragma__ ('skip')
from interfaces.document import document
from interfaces.math import Math
#__pragma__ ('noskip')
`

