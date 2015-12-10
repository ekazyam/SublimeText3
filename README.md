#Sublime Text 3 Settings for windows

Key assignment to the mouse
---

### Installation location

~~~
Sublime Text 3\Packages\User
~~~

### Setting File

~~~
Default (Windows).sublime-mousemap
~~~

### seting example

~~~
[
	{
    	// when pressed ctrl + mounse button 1
        // jump to definiton source.
        "button": "button1",
        "count": 1,
        "modifiers": ["ctrl"],
        "press_command": "drag_select",
        "command": "goto_definition"
    }
    ,{
    	// when pressed mouse button 4
        // jump to calling source.
        "button": "button4",
        "count": 1,
        "command": "jump_back"
    }
]
~~~

License
---
This software is released under the MIT License, see LICENSE.
