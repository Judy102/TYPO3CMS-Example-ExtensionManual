.. include:: ../Includes.txt


.. _einfuehrung:

Einführung
============


.. _Worum-geht-es:

Worum geht es?
---------------
Evalanche der Firma `SC-Networks <http://www.sc-networks.de/>`_ umfasst eine umfangreiche Lösung für Email-Marketing-Automation, wodurch sich der hohe Aufwand bei der Planung und Durchführung von Email-Kampagnen minimieren lässt. Zum Einsatz kommt Evalanche überwiegend in Agenturen und größeren Unternehmen, welche von der vereinfachten Handhabung bei Kampagnen profitieren. Die IMIA Evalanche Extension stellt hierfür eine geeignete Schnittstelle zu dem TYPO3 CMS zur Verfügung, sodass Evalanche vereinfacht verwendet und darauf zugegriffen werden kann.
|**WICHTIG:** Für die optimale Anwendung aller Funktionen der IMIA Evalanche Extension ist es notwendig die IMIA User Extension ebenfalls zu installieren, da hierdurch das Anlegen von Benutzerdaten vereinheitlicht wird und auf bestehende Normen zugegriffen werden kann.

Funktionen
^^^^^^^^^^^
**1. :ref:`Evalanche-Formulare`**
- Es können eigene Formulare angelegt werden, welche von dem User ausgefüllt und die Parameter direkt an Evalanche weitergeleitet werden (ohne zusätzliches iFrame und unabhängig vom TYPO3)   

**2. :ref:`automatischer-Synchronisierung`**
- Es findet eine automatisierte Synchronisierung von Benutzerdaten bzw. Kontakten statt, welche an Evalanche übertragen werden

**3. :ref:`anreicherung-von-Smartlinks`**
- automatische Anreicherung von Smartlinks mit Benutzerparametern und Prüfung auf die jeweilige Gültigkeit


.. _Evalanche-Formulare:
1. Evalanche-Formulare
"""""""""""""""""""""""""

Der Benutzer kann selbst im Content-Bereich bestimmen wo ein Formular eingefügt werden soll und ob es zu Evalanche weitergeleitet wird. Sobald er ein entsprechendes Formular gewählt hat, kann er als Redakteur sämtliche Felder anpassen oder sogar vorab automatisch befüllen lassen.

.. figure:: ../Images/20-10-_2016_17-06-28.jpg
   :width: 700px
   :alt: eigene Formulare anlegen
   
   
Ebenso besteht die Möglichkeit ein vorab erstelltes Formular zu wählen und erneut zu verwenden. Alle Formulare können mit eigenen Styles und Scripten angereichert und somit ganz individuell an die eigenen Wünsche angepasst werden. Sobald ein Kunde nun im Frontend seine Daten in das Formular einträgt und absendet, werden diese direkt an Evalanche weitergeleitet, ohne zusätzliche Zwischenspeicherung im TYPO3 Backend. Ebenso ist kein zusätzliches iFrame nötig, welches eingebunden werden müsste um die Daten zu übertragen. Alle geschieht automatisch dank der IMIA Evalanche Extension. Mehr Details unter ":ref:`user-manual`"


.. _automatischer-Synchronisierung:
2. automatische Synchronisierung
""""""""""""""""""""""""""""""""""

Mit Hilfe der IMIA Evalanche können angelegte Benutzer in einem globalen Ordner verwaltet werden. Sobald der Ordner der Erweiterung "Evalanche Sync" zugewiesen ist, greift die Extension und synchronisiert automatisch die Daten auf die Evalanche Plattform. 

.. figure:: ../Images/18-10-_2016_15-16-23.jpg
   :width: 700px
   :alt: Synchronisierung einrichten

Die Synchronisation kann separat eingestellt und angepasst werden, sodass der Administrator selbst bestimmen kann, wann diese automatisch durchgeführt wird. Eine unumgängliche Vorraussetzung zum Verwenden der Extension ist ein bestehendes Evalanche-Konto, da es notwendig ist in den Einstellungen der Erweiterung einmalig die Login-Daten für Evalanche zu hinterlegen. Mehr Details unter ":ref:`synchronisation-configuration`"

   
.. _anreicherung-von-Smartlinks:
3. Anreicherung von Smartlinks
""""""""""""""""""""""""""""""""

Durch den Einsatz von Smartlinks kann ganz simpel das Verhalten der Emailempfänger getrackt werden. Sobald ein Kunde einen Link in der Mail anklickt, werden seine Benutzerdaten an diesen getagt und mit übergeben, sodass wertvolle Informationen über das Kundenverhalten gewonnen, oder auch spezielle Formularfelder mit den Daten vorab automatisch ausgefüllt werden können. Durch die IMIA Evalanche Extension kann sichergestellt werden, dass die Smartlinks gültig und richtig gesetzt werden. Somit können die Informationen verlustfrei an Evalanche übermittelt werden. Die Verwendung von Smartlinks kann ganz simpel in den Einstellungen der Erweiterungen angegeben werden, in dem einfach ein Smartlink in das vorgesehene Feld eingetragen wird. Mehr Details unter ":ref:`smartlink-configuration`"
