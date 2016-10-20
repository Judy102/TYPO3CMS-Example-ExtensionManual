.. include:: ../Includes.txt


.. _admin-manual:

Administrator Anleitung
=======================

Eine Vorraussetzung zur Anwendung der IMIA Evalanche Extension ist die Installation der IMIA User Extension. Ohne diese Erweiterung ist die Übertragung und Synchronisation der Benutzerdaten mit Evalanche nicht möglich. 

.. _admin-installation:

Installation
------------

Um die Extension zu installieren müssen folgende Schritte befolgt werde:

#. Auf "Erweiterungen" klicken
#. Nach "IMIA Evalanche" suchen und die Extension auswählen
#. Importieren und installieren


.. _admin-configuration:

Configuration
-------------


Synchronisation 
---------------

In jedem Typo3 CMS gibt es mindestens einen Administrator, welcher unter anderem die einzelnen Extensions vorkonfiguriert, damit die Redaktuere sie problemlos verwenden können. Ebenso gilt es bei der IMIA Evalanche Extension nach dem Download und der Installation einige wichtige Einstellungen zu berücksichtigen. Damit die Synchronisation der Benutzerdaten mit Evalanche erfolgen kann, muss in den Einstellungen der Extension der Login hinterlegt werden um einen Zugang zu der Evalanche Software zu ermöglichen. Dies umfasst die Evalanche-URL, den Nutzernamen und das Passwort.

.. figure:: ../Images/18-10-_2016_13-19-18.jpg
   :width: 500px
   :alt: Synchronisation
   

Durch die Einrichtung des Scheduler (Planer) im Typo3 Backend kann nun entschieden werden, wann ein automatisierter Synchronisationsvorgang vorgenommern wird. Hierbei wird ein neuer Task angelegt um Zielzeiten des Vorgangs zu wählen, die Häufigkeit der Synchronisation anzugeben oder parallele Ausführungen zu erlauben. Es gilt zu beachten dass in dem Auswahlmenü "CommandController Command" die ImiaEvalanche Sync ausgewählt wird, um die Synchronisation der richtigen Extension zu gewährleisten. Das Feld "Argument: poolID" dient hierbei zur genauen Identifikation des Pools in welchen die Kontakte gespeichert werden sollen in Evalanche. 

.. figure:: ../Images/20-10-_2016_17-34-39.jpg
   :width: 500px
   :alt: Einstellungen Planer Task
   
   
In einem globalen Ordner können nun sämtliche Kontakte und Benutzerdaten hinterlegt werden, welche an Evalanche übertragen werden sollen. Sobald bei der Bearbeitung des Ordners die Evalanche Sync in den Erweiterungen eingestellt wird, greift der Scheduler auf die Daten zu und synchronisiert alle Inhalte mit dem Evalanche-System und in den dafür vorgesehenen Pool.
