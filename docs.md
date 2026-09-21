# Starflight supernova (rendream) docs





##### objects \& tables



###### getOBJ(objID)

gets an Object from Rendering Table based on ID



###### getRendreamVar()

returns the rendering table



###### switchLevel(levelnum)

switches the current Rendream Level



###### setRendream(Table)

sets the Rendream rendering table



###### setVar(name, value)

sets Rendream variable to value



###### getVar(name)

gets Rendream variable



##### player control



###### resetplr()

resets player to start pos



###### plrPOS(X,Y)

set the player position



###### getPlrPOS()

returns player X and Y positions



###### setGravity(number)

changes gravity



###### playerConstraint(input)

disables an input



###### setInput(input, keybinding)

sets an input to a different keybinding



###### inputs



|**input name**|**default bindng**|
|-|-|
|right|"ArrowRight"|
|left|"ArrowLeft"|
|jump|space (" ")|
|up|"ArrowUp"|
|down|"ArrowDown"|





##### rendream



###### reDream()

resets Engine



###### fastReDream()

resets current level



###### isKeyDown()

checks if a key is pressed



###### checkCollision(ObjectA, ObjectB)

checks collision between two objects



###### setVar(variable\_name,value)

set Rendream Variable

###### getVar(variable\_name,value)

get Rendream Variable

###### editLevelProperty(property\_name,value)

set Rendream level property

###### properties



|**property name**|**default value**|
|-|-|
|outline|`false`|
|outline\_thickness|`0`|
|outline\_color|`#000000`|
|death\_height|`1001`|
|UI\_outlineUI|`false`|
|UI\_outline\_thickness|`0`|
|UI\_outline\_color|`#000000`|
|property12|`false`|

#### rendering



###### addBlankObject(x,y,width,height,color,id)

add a blank object



###### updateCam(target, isSmooth, smoothing)

updates camera position





###### updateText(textObject, text)

changes text object text



###### onButtonClick(object, callback)

runs `callback` when UIButton object is clicked

