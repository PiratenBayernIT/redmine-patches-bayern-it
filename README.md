Redmine patches
===============


messenger.yml
-------------

* Config für messenger Plugin
* Pass muss noch eingefgt werden

get\_mail
---------

* einfaches Rake-Script um Mails vom IMAP-Server zu holen
* es muss einiges ergänzt werden, vor allem Username und Passwort für den Mailbenutzer

mailer\_issue.html.erb.patch
----------------------------

* sortiert die Reihenfolge in Benachrichtigungs-Mails ein wenig um
** Zeiten und Custom fields nach oben

issues\_helper.patch
--------------------

* Custom fields für Tooltips im Kalender 


mailer.rb.patch
---------------

* voller Projektpfad im Benachrichtungsmail-Betreff
* führt aber teilweise zu langen Betreffzeilen, Vorsicht...
* Projekte immer eindeutig zu benennen ist einfacher



