=================
Syntax
=================

.. note::
   This is note text. Use a note for information you want the user to
   pay particular attention to.

   If note text runs over a line, make sure the lines wrap and are indented to
   the same level as the note tag. If formatting is incorrect, part of the note
   might not render in the HTML output.

   Notes can have more than one paragraph. Successive paragraphs must
   indent to the same level as the rest of the note.
   
.. warning::
   This is warning text. Use a warning for information the user must
   understand to avoid negative consequences.

   Warnings are formatted in the same way as notes. In the same way,
   lines must be broken and indented under the warning tag.
   
.. seealso:: This is a simple **seealso** note.

.. tip:: This is tip

.. important:: This is important block

.. attention:: This is attention block
   
.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.


.. sectionauthor:: John Smith <js@python.org>

.. comments
   this comments
   1234

Topic Title
###########

High-level overview of topic.

What is ?
**********

High level conceptual information (Heading 2).

At a minimum, a concept includes the following components.

* A title, phrased as a gerund or question.
* One or more body paragraphs.

Complex concepts may contain 2 or more subsections.

What is <part of subject> ?
============================

When you need to break down a subject, you can break it down into subsections (H3s). Typically you would have 0 H3s, or 2+ H3s.


What is <part of subject> ?
============================

When you need to break down a subject, you can break it down into subsections (H3s)

Do this
**********

A task typically follows conceptual information. Task titles should be imperative. Tasks should have a short introduction sentence that captures the user's goal and introduces the steps, for example, "Verify your products are in the catalog:"

A task should have 3 - 7 steps.  Tasks with more should be broken down into digestible chunks.

Intro sentence.

#. Step 1.

#. Step 2.

#. Step 3.

Following the steps, you should add the result and any follow-up tasks needed.

:download:`download fan.png <../_images/fan.png>`

   
.. figure:: ../_images/fan.png
   :scale: 50 %
   :align: left
   :alt: map to buried treasure
   
.. figure:: ../_images/fan.png
   :scale: 50 %
   :align: center
   :alt: map to buried treasure
   
.. figure:: ../_images/fan.png
   :scale: 50 %
   :align: right
   :alt: map to buried treasure

   This is the caption of the figure (a simple paragraph).

   The legend consists of all elements after the caption.  In this
   case, the legend consists of this paragraph and the following
   table:

	.. |pic1| image:: ../_images/fan.png
	  :scale: 15%
	  	  
	.. |pic2| image:: ../_images/fan.png
	  :scale: 25%
	  	  
	.. |pic3| image:: ../_images/fan.png
	  :scale: 35%
	  
	+----------+-------------+ 
	| Symbol   |  Meaning    | 
	+==========+=============+ 
	| |pic1|   | Campground  |
	+----------+-------------+ 
	| |pic2|   | Lake        | 
	+----------+-------------+ 
	| |pic3|   | Mountain    | 
	+----------+-------------+ 
   
|pic4| any text |pic5|

.. |pic4| image:: ../_images/fan.png
   :scale: 25%

.. |pic5| image:: ../_images/fan.png
   :scale: 15%
   
.. |Substitution Name| image:: ../_images/fan.png
  :scale: 25%
  :alt: Alternative text

The screen opens:

|Substitution Name|
   
.. |current-time| date:: %Y-%m-%d %H:%M:%S

.. |date| date::
.. |time| date:: %H:%M

Today's date is |date|.

This document was generated on |date| at |time|.


.. epigraph::

   No matter where you go, there you are.

   -- Buckaroo Banzai
   
.. compound::

   The 'rm' command is very dangerous.  If you are logged
   in as root and enter ::

       cd /
       rm -rf *

   you will erase the entire contents of your file system.
   
google_

.. _google: http://www.google.com.tw/


前往 `google`__

__ www.google.com.tw
   
.. this is comment

..
   this is comment
   this on
   
   this also 
   
你有把我\ **放在心上**\ ，有嗎！

``$sudo yum install pygame``

::

    $sudo yum install pygame
    $sudo yum install python
    $sudo yum install python-pip
	
.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'