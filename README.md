strassenfeste
=============
Angeregt vom Artikel "Reifeprüfung fürs Web" im Linux-Magazin (http://www.linux-magazin.de/Ausgaben/2013/11/Einfuehrung3).

Leider wurde Perl einfach nicht berücksichtigt...

Installation
============
   * Perl installieren (Version >= 5.10.1)
   * auf der Konsole
      * cpan install Mojolicious
      * git clone .../strassenfeste
      * cd strassenfeste
      * morbo strassenfeste (verwendet die lokale Kopie der Strassenfeste)
      * morbo strassenfeste -m production (verwendet die live-Version der Strassenfeste; mit Caching)
      * http://localhost:3000/
