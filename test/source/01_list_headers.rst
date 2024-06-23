lists
#################
.. Every file must contain a header 
   # - Defines it as the main header or High-level overview of topic.
   Remember number of # must be equal to or greater than the letters in the heading

This contains overview about lists
************************************
.. * - This symbolises what does the document contain

Ordered lists
==============
.. = - Defines the sub topic level

#. Step1
#. Step2
#. Step 3

.. #. - This is for numbered bulleting

Ordered lists under ordered lists
----------------------------------
.. - symbol defines the level within the subtopic level
   basically = * = - is how you write sections in a document

#. Step4
    #. Content 1
    #. Content 2
#. Step 5
    #. Content 3
    #. Content 4


Unordered lists 
================
.. This is another sub topic level which comes under the highlevel topic called lists, and not under the level of "Ordered level"

 * Item1
 * Item2
 * Item3
.. * - Defines non-numbered bulleting

Unordered list inside ordered list
-----------------------------------
.. This is a topic which comes under "Unordered lists"

#. page1
    * Item1
    * Item2
#. page2
    * Item3

Unordered List Inside Unordered List
-------------------------------------

* Page1
    * content 1
    * content 2
* Page 2
    * Content 3
    * Content 4

Including code inside lists
****************************************
 .. The symbol which tells the sphinx that the following is a code is "::"

 * A code in python

 #. Step 1

      To print hello  :: 

        print("hello")
        
 #. Step 2
    
        Do a for loop ::

            for i in range(10):
                print(i)

