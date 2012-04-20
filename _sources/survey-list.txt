.. _survey-list:

***********
Survey List
***********



After logging in the list of surveys that are available for that user are shown

.. figure:: images/survey.png
   :scale: 80 %
   :width: 80%
   :alt: Surveys
 
   Survey List

with each survey having a **SURVEY NAME**, **DATE**, **PUBLISHER** and a number of **RESULTS** sent back for that survey. If responses have come back for a particular survey then the number of responses becomes a link to the :doc:`results` page.


Surveys can be filtered by clicking on either **Building** or **Available** 


.. figure:: images/building.png
   :scale: 80 %
   :width: 80%
   :alt: Filter

   Survey Filter to show only surveys currently being built

and to return to the default list showing all surveys (i.e to turn off the filter) click the red highlighted text. Surveys are made **Available** by being sent to a device. After a survey is made **Available** it can no longer be edited. It can however be duplicated and then edited again. To do this click the duplicate icon on the survey toolbar.

.. figure:: images/duplicate.png
   :scale: 80 %
   :width: 80%
   :alt: Duplicate

   Duplicate a survey


The new duplicated survey can be edited and saved as needed until it is sent to a device. Then its **Building** status will change to **Available** and no further editing is allowed. Such a process is an easy way to implement simple version control for surveys.

Other functions available in the survey toolbar are (in order) **Download**, **Upload**, **Send**, **Edit** and **Delete**.

Clicking **Download** opens a browser File Save dialog and the raw survey xml can be saved. This is a useful function if for example the survey can only be passed onto a device using USB or bluetooth as may be the case if no cellular network is available. 


.. figure:: images/download.png
   :scale: 80 %
   :width: 80%
   :alt: Download

   Download a survey


**Upload** is the same process but in reverse and is only available when **Building** surveys.

.. figure:: images/upload.png
   :scale: 80 %
   :width: 80%
   :alt: Upload Survey

   Survey Upload dialog box

and is a useful function if for example a user has an existing survey created using another Open Rosa compatible survey builder that they wish to use with Nokia Data Gathering. Clicking **Send** presents a list of Users and their corresponding telephone numbers

.. figure:: images/send.png
   :scale: 80 %
   :width: 80%
   :alt: Send Survey

   Send Survey dialog with Usernames and Phone Numbers

select the check box next to the Username and then the Done button to send the survey to that user. 

The final button on the survey toolbar is **Edit** and clicking this on a survey in the **Building** state shows the :doc:`editor` which is integrated in Nokia Data Gathering. If rather than editing an existing survey you would like to create a new one click the plus + icon


.. figure:: images/add-survey.png
   :scale: 80 %
   :width: 80%
   :alt: Add survey

   Survey Creation


