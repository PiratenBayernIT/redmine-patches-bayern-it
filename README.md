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


mailer.rb-2.patch
-----------------

* Hack für Mailman-Sync: Termin-Änderungen, die nicht "Bestätigt" oder "Abgesagt" sind, bekommen den Header
    "X-Redmine-No-Mailinglist: true" gesetzt und können damit einfach ausgefiltert werden.


issues_new.html.erb.patch
-------------------------

* Hook hinzugefügt, um Elemente unten in die Watchers-Box hinzuzufügen. Wird genutzt, um redmine_watchers_by_group in der modifizierten Form einzubauen.


de.yml.patch
------------

Paar Uebersetzungs-Anpassungen, damit das Ganze besser zu Parteiarbeit passt.
