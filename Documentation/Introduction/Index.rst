.. include:: ../Includes.txt


.. _einfuehrung:

Einführung
============


.. _Worum-geht-es:

Worum geht es?
----------------

Evalanche der Firma SC-Networks (http://www.sc-networks.de/) umfasst eine umfangreiche Lösung für Email-Marketing-Automation wodurch sich der hohe Aufwand bei der Planung und Durchführung von Email-Kampagnen minimieren lässt. Die Extension "IMIA Evalanche" stellt hierfür eine geeignete Schnittstelle zu dem CMS Typo3 zur Verfügung, sodass Evalanche vereinfacht verwendet und darauf zugegriffen werden kann:

   .. _Formulare_erstellen:
   1. Es können eigene Formulare angelegt werden, welche von dem User ausgefüllt und die Parameter direkt an Evalanche weitergeleitet
   werden (ohne zusätzliches iFrame und unabhängig vom Typo3)
   .. _:
   2. Es findet eine automatisierte Synchronisierung von Benutzerdaten statt, welche an Evalanche übertragen werden sollen
   3. vereinfacht Smartlinks eingefügt werden, wodurch Evalanche das Nutzerverhalten trackt und automatisch Felder befüllen kann


.. important::

   Please don't forget to repeat your extension's version number in the
   :file:`Settings.yml` file, in the :code:`release` property. It will be
   automatically picked up on the cover page by the :code:`|release|`
   substitution.

