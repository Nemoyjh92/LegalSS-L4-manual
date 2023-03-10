.. _Learning L4_exercises:

#########
Exercises
#########

You may find the :ref:`L4 Spreadsheet quick reference` helpful.

-----------------------------------------
Formalising Simple Rules: Liquor Exercise
-----------------------------------------

The example provided in L4's "Must Sing" example is "A person who walks, and eats, or drinks, must sing."

Liquor laws vary in many countries, but most have some constraints on who can buy liquor. Imagine you are an internationally trained lawyer intimately familiar with liquor laws in Singapore and America and are trying to implement a fragment of it into the L4 language.

Task: Implement, in L4, the following legal exercises:

You are given the following rule in the tab "Learning L4: Liquor Exercise". You should note that:

- Words in **bold** are keywords and in this example, they are in all-caps to stand out.

- Yellow cells are where you should type your answer.

- Comments in L4 begin with two backslashes, ``\\ like this``.

- Gray cells are for comments

1. A person **WHO** is 21, **AND** is **NOT** located within the Little India **OR** Geylang liquor control zones, **MAY** buy liquor.

.. image:: ../images/liquor-exercise-start.png
  :class: with-border

**Edit the above rule in L4 to reflect the following**, keywords are still in **bold** but they are not in all-caps.
   
2. A person **who** is 21, **and** has cash, **or** a credit card, **and** is **not** located within the Little India **or** Geylang liquor control zones, **may** buy liquor

You will have succeeded if you obtain the following diagrams:

.. image:: ../images/Pastedimage20230114164121.png
  :class: with-border

.. image:: ../images/Pastedimage20230114164043.png
  :class: with-border

.. image:: ../images/Pastedimage20230114164104.png
  :class: with-border

**Now, implement the following rule in a new tab in your spreadsheet**. Now keywords are neither in bold nor in all-caps!

3. A person who is not in Michigan, and not in Mississipi, and knows a shop nearby, may buy liquor.

You will have succeeded if you obtain the following diagrams:

.. image:: ../images/Pastedimage20230114164601.png

.. image:: ../images/Pastedimage20230114164523.png

.. image:: ../images/Pastedimage20230114164537.png

.. _L4 Spreadsheet quick reference:

-----------------------------------
LegalSS spreadsheet quick reference
-----------------------------------

- **Adding tabs to Google Sheets**: Click the plus sign on the bottom-left hand corner of your screen, next to where you can find the google sheet tabs.

.. image:: ../images/new-tab.png

- **Sidebar auto-refresh**: You can stop auto-refresh by highlighting the cells you are typing in in a shade of grey. To enable auto-refresh, highlight the cells you are typing in back to white, make a minor change, and then wait for refresh.

If the sidebar is not refreshing at all, re-run the Apps script from step 2 of :ref:`sheets_ide`.

.. image:: ../images/grey-colouring.png

- **Adding comments to the LegalSS Google Sheets**: Comments have a grey background and start with '//'.

--------------------------------------------------------
Parantheses and Operator precedence: Arithmetic Exercise
--------------------------------------------------------

This exercise will introduce parantheses and operator precedence


-----------------------
Data Modelling Exercise
-----------------------

This exercise will teach you how to model sentences like:

  - Every company has shareholders, 
  - Every company has directors, 
  - Every company has a mailing address

------------------------------------------
Modelling Simple Obligations and Deadlines
------------------------------------------

This exercise will allow you to model obligations such as an exchange of money for goods.