# Mouse Tweaks API

## IMTModGuiContainer2

If your container isn't based on GuiContainer, or if you want to improve compatibility (marking certain slots as ignored
by the mod as an example), take a look at this interface. Implement it on your GuiScreen-based container.

## IMTModGuiContainer2Ex

An extended version of the previous interface, adds an ability to override the slot clicking function, as well as an
ability to set priority for the mouse scroll action to put certain items in slots. For example, prioritizing coal into the Fuel slot of a Furnace.

## @MouseTweaksIgnore

Putting this annotation on your GuiContainer is a quick and easy way to disable Mouse Tweaks on the container without
having to implement the whole API interface.

## @MouseTweaksDisableWheelTweak

Putting this annotation on your GuiContainer is a quick and easy way to disable the wheel tweak on the container without
having to implement the whole API interface.

## IMTModGuiContainer

This is an old, deprecated and bad interface which you shouldn't use.
