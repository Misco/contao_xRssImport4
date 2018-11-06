# contao_xRssImport4
contao_xRssImport3 for Contao 4 Php7

zum Beispiel zur Übernahme von Wordpress Beiträgen

Orginal forked from katgirl/contao_xRssImport3

xRssImport4
RSS Nachrichten-Import für Contao ab 4.6 should work in other contao 4 also

Hinweise
Beiträge können nur gelöscht werden, wenn diese auch im Feed nicht mehr existieren, ansonsten werden sie wieder neu bezogen. Besser ist des, den Beitrag zu deaktivieren.
Ein Import findet übder den Command-Scheduler jede Stunde statt. Darüber hinaus kann auch mit der cron-Erweiterung importiert werden. Dazu muss im Job als Pfad system/modules/xRssImport3/jobs/importAllNews.php eingetragen werden.
Die Einbettung von Bildern funktioniert nur dann, wenn diese als Anlage (enclosure) mitgeliefert werden.
