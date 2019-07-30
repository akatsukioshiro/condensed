# condensed
* _Example Website : main.html (Check Code)_
* _**Exponentially**_ reduced _webpage generation time_. 
* _Utility script_ with _**Javascript parser**_.
* Script syntax is similar to _SQL_.
* Simplicity with improved Functionality.
* Currently unique _tagnames_ required.
* Creativity via TAG based 'css' is fully functional.
* __Development Phases :__
  * Simplicity _~ Alpha Stage_
  * Instant Websites _~ Beta Stage_
  * HTML WEBcodes _~ Gamma Stage_
  * SML _~ Lambda Stage_
* __BASIC Necessary Instructions :__
  * No need to use <\html\>\</html>,\<head\>\</head\>,\<body\>\</body\> in chrome browser.
  * Add <\html\>\</html>,\<head\>\</head\>,\<body\>\</body\> to support mostly all browsers.
  * \<body\>\</body\> is where all code is expected to be placed.
  * __\<!DOCTYPE html\>__ is mandatory.
  * __Script.js__ is mandatory .js File to be added only after 'Element Definition' phase.
  * Add stylesheet at the end.
  * Each statement must begin with a __dollar character "$"__, it is a special character so do not use it elsewhere.
* __Special Character List :__
  * __DOLLAR CHARACTER : $__ is used to end a statement.
  * __COMMA     : ,__ is used to separate child element names in _**where**_ keyword.
  * __SEMICOLON : ;__ is used to separate _id_ and _class_ of child elements in _**with**_ keyword.
  * __EQUALS + PIPE : =|__ is used in **remake** to separate _addingtype_ and _addingcontent_.
  * __BRACKETS  :__ 
    * __()__ is used to enclose _id_, _class_ and other attributes of child elements in _**with**_ keyword.
* **Keyword List :**
  * **make :** 
    * creates div.
    * Syntax : make *element_name*
    * Additional attributes (if necessary either or both can be added) :
      - *__id__=idname*
      - *__class__=classname*
      - Syntax : __make__ *element_name* *__id__=idname* *__class__=classname*
  * **in :**
    * appends div in chosen parent element.
    * by default all elements will be created in *box* tag under body if *in* keyword not used.
    * Syntax : __make__ *child_element* __in__ *parent_element_of_your_choice*
  * **with :**
    * adds child elements while parent creation.
    * Child element names are separated by space.
    * Syntax : make *element_name* with *child1* *child2* *child3*
    * Additional child attributes (if necessary either or both can be added) :
      - *(__id__=idname;)*
      - *(__class__=classname;)*
      - *(height-with-heaight-type \* width-with-widthtype;)*
      - Syntax : __make__ *element_name* __with__ *childelement(__id__=idname;__class__=classname;height-with-heaight-type \* width-with-widthtype)*
  * **where :**
    * used to select an element/elements to define it further.
    * has following attributes :
      - **and** : *and* is used to define an *element* clickable as well as *editable to accept input*.
      - **all** : *all* is used to select all *sibling elements* to define property.
      - **is/are clickable** is used to provide *elements* with _onclick_ functionality along with _dynamic function names_.
      - **take/takes input** is used to make *elements* accept *text input*.
      - **is/are draggable** is used to provide *elements* with _draggable_ functionality.
    * **SYNTAX EXAMPLES :**
      - **Type 1 :**  
        * Syntax : __make__ *element_name* __with__ *child1* *child2* __where__ *child1*,*child2* are clickable
        * Syntax : __make__ *element_name* __with__ *child1* *child2* __where__ *all* are clickable
        * **ABOVE 2 Syntaxes show example that produce SAME RESULTS.**
        * *draggable* attribute uses same syntax.
      - **Type 2 :**  
        * Syntax : __make__ *element_name* __with__ *child1* *child2* __where__ *child1*,*child2* take input
        * Syntax : __make__ *element_name* __with__ *child1* *child2* __where__ *all* take input
        * **ABOVE 2 Syntaxes show example that produce SAME RESULTS.**
  * **remake :**
    * selects div to add text, image etc.
    * Attribute list :
      * having : (compulsory)
        * used to select id of element. 
      * adding : (compulsory)
        * used to add text, image etc.
        * Supported types :
          * Text
          * Image
    * Syntax : **remake** *element_name* **having** id=_idname_ **adding** text=|_textcontent_
    * Syntax : **remake** *element_name* **having** id=_idname_ **adding** image=|_imageurl_

