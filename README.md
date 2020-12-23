# widget_calculateUrlBack
You display a form, and when the user submits, you want to come back where you were (Portal, Custom Page, Living Application)? This widget is for you.

1/ Add the widget to your page

2/ create a STRING variable, named (for example) it **formUrlBack**

3/ reference this **formUrlBack** variable in the widget, in the property **urlBack**

4/ in your button, in property **Target URL on success**, set the value to **{{formUrlBack}}**

