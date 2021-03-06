---

copyright:
  years: 2015, 2018
lastupdated: "2017-11-06"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

<!-- Acrolinx: 2017-03-06 -->

# Unterstützte Clientbibliotheken

## Mobil

Die {{site.data.keyword.cloudantfull}} Sync-Bibliothek wird zum Speichern,
Indizieren und Abfragen lokaler JSON-Daten auf einem mobilen Gerät verwendet.
Sie wird außerdem zum Synchronisieren von Daten zwischen einer Vielzahl von
Geräten verwendet.
Die Synchronisierung wird von Ihrer Anwendung gesteuert.
Die
Bibliothek stellt außerdem Helper-Methoden zum Aufspüren und Lösen von
Konflikten auf dem lokalen Gerät sowie in der fernen Datenbank bereit.

Es sind zwei Versionen verfügbar:

-   [{{site.data.keyword.cloudant_short_notm}} Sync - Android / JavaSE ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/sync-android){:new_window}.
-   [{{site.data.keyword.cloudant_short_notm}} Sync - iOS (CDTDatastore) ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/CDTDatastore){:new_window}.

Eine [Übersicht ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://cloudant.com/product/cloudant-features/sync/){:new_window} zu {{site.data.keyword.cloudant_short_notm}} Sync ist verfügbar.
Details zu {{site.data.keyword.cloudant_short_notm}} Sync-[Ressourcen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://cloudant.com/cloudant-sync-resources/){:new_window} sind ebenfalls verfügbar.

## Java

[java-cloudant ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/java-cloudant){:new_window} ist die offizielle
{{site.data.keyword.cloudantfull}}-Bibliothek für Java.

Informationen zur Installation der Bibliothek durch ihr Hinzufügen als Abhängigkeit
zu Ihren Maven- oder Gradle-Builds sind
[hier ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/java-cloudant#installation-and-usage){:new_window},
mit Details und Beispielen zur Verwendung der Bibliothek verfügbar.

### Bibliotheken und Frameworks

#### Unterstützt

-   [java-cloudant ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/java-cloudant){:new_window}.

#### Nicht unterstützt

-   [ektorp ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://ektorp.org/){:new_window}.
-   [jcouchdb ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://code.google.com/p/jcouchdb/){:new_window}.
-   [jrelax ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/isterin/jrelax){:new_window}.
-   [LightCouch ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://www.lightcouch.org/){:new_window}.
-   [Java {{site.data.keyword.cloudant_short_notm}} Web Starter ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://ace.ng.bluemix.net/#/store/cloudOEPaneId=store&appTemplateGuid=CloudantJavaBPTemplate&fromCatalog=true){:new_window} - Boilerplate für Bluemix.

### Beispiele und Lernprogramme

-   [Erstellen, Lesen, Aktualisieren und Löschen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/haengematte/tree/master/java){:new_window} mit HTTP- und JSON-Bibliotheken.
-   [Erstellen, Lesen, Aktualisieren und Löschen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/haengematte/tree/master/java/CrudWithEktorp){:new_window} mit der 'ektorp'-Bibliothek.
-   [Apps mithilfe von Java mit {{site.data.keyword.cloudant_short_notm}} unter IBM Bluemix erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://cloudant.com/blog/building-apps-using-java-with-cloudant-on-ibm-bluemix/){:new_window}.
-   [Spiele-App mit Liberty, {{site.data.keyword.cloudant_short_notm}} und Single Sign On erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://www.ibm.com/developerworks/cloud/library/cl-multiservicegame-app/index.html?ca=drs-){:new_window}, Bluemix-Beispiel.
-   [Java EE-App unter IBM Bluemix mithilfe von Watson und {{site.data.keyword.cloudant_short_notm}} erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://developer.ibm.com/bluemix/2014/10/17/building-java-ee-app-ibm-bluemix-using-watson-cloudant/){:new_window}, Bluemix-Beispiel mit [YouTube-Video ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://www.youtube.com/watch?feature=youtu.be&v=9AFMY6m0LIU&app=desktop){:new_window}.


## Node.js

[nodejs-cloudant ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/nodejs-cloudant){:new_window}
ist die offizielle {{site.data.keyword.cloudant_short_notm}}-Bibliothek für Node.js.
Sie können
die Installation mit npm durchführen:

```sh
npm install cloudant
```
{:codeblock}

### Bibliotheken und Frameworks

#### Unterstützt

-   [nodejs-cloudant ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/nodejs-cloudant){:new_window} ([npm ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://www.npmjs.org/package/cloudant){:new_window}).

#### Nicht unterstützt

-   [sag-js ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/sbisbee/sag-js){:new_window}, die auch im Browser funktioniert.
    Weitere Details finden Sie unter [saggingcouch ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/sbisbee/saggingcouch.com){:new_window}.
-   [nano ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/dscape/nano){:new_window} ist eine minimalistische Implementierung.
-   [restler ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/danwrong/restler){:new_window} liefert die beste Leistung, aber es handelt sich um eine wirklich abgespeckte Version.
-   [cradle ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/flatiron/cradle){:new_window} ist ein übergeordneter Client, der sich auch dann eignet,
    wenn Benutzerfreundlichkeit Vorrang hat vor den Kosten einer geringeren Leistung.
-   [cane_passport ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/ddemichele/cane_passport){:new_window} - {{site.data.keyword.cloudant_short_notm}} Angular Node Express mit Bootstrap.
-   [express-cloudant ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant-labs/express-cloudant){:new_window} - eine Vorlage für das Node.js Express-Framework, das auch PouchDB und Grunt nutzt.
-   [Node.js {{site.data.keyword.cloudant_short_notm}} DB Web Starter ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://ace.ng.bluemix.net/#/store/cloudOEPaneId=store&appTemplateGuid=nodejscloudantbp&fromCatalog=true){:new_window} - Boilerplate für Bluemix.
-   [Mobile Cloud ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://ace.ng.bluemix.net/#/store/cloudOEPaneId=store&appTemplateGuid=mobileBackendStarter&fromCatalog=true){:new_window} - Boilerplate für Bluemix (Node.js, Security, Push und Mobile Data/{{site.data.keyword.cloudant_short_notm}}).

### Beispiele und Lernprogramme

-   [Erstellen, Lesen, Aktualisieren und Löschen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/haengematte/tree/master/nodejs){:new_window}.
-   [Cloudant-Uploader ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/garbados/Cloudant-Uploader){:new_window} - Dienstprogramm zum Hochladen von `.csv`-Dateien nach {{site.data.keyword.cloudant_short_notm}}.
-   [couchimport ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/glynnbird/couchimport){:new_window} - Dienstprogramm zum Importieren von `.csv`- oder `.tsv`-Dateien in CouchDB oder {{site.data.keyword.cloudant_short_notm}}.
-   [Einführung in {{site.data.keyword.Bluemix}} und Node.js ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://thoughtsoncloud.com/2014/07/getting-started-ibm-bluemix-node-js/){:new_window}.
-   [Ein Cloud-Medley mit {{site.data.keyword.Bluemix_notm}}, {{site.data.keyword.cloudant_short_notm}} und Node.js ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://gigadom.wordpress.com/2014/08/15/a-cloud-medley-with-ibm-bluemix-cloudant-db-and-node-js/){:new_window}.
-   [Einfache Wortspiel-App mithilfe von {{site.data.keyword.cloudant_short_notm}} unter {{site.data.keyword.Bluemix_notm}} erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://www.ibm.com/developerworks/cloud/library/cl-guesstheword-app/index.html?ca=drs-){:new_window} - verwendet Node.js.
-   [App für Echtzeitabstimmung per SMS erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://www.twilio.com/blog/2012/09/building-a-real-time-sms-voting-app-part-1-node-js-couchdb.html){:new_window} - sechsteilige Serie zur Verwendung von Node.js, Twilio und {{site.data.keyword.cloudant_short_notm}}.
-   [Mehrschichtige Windows Azure-Webanwendung erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://msopentech.com/blog/2013/12/19/tutorial-building-multi-tier-windows-azure-web-application-use-cloudants-couchdb-service-node-js-cors-grunt-2/){:new_window} - nutzt {{site.data.keyword.cloudant_short_notm}}, Node.js, CORS und Grunt.
-   [Do it yourself: Fernüberwachungsanwendung mit {{site.data.keyword.Bluemix_notm}}, {{site.data.keyword.cloudant_short_notm}} und Raspberry Pi erstellen ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](http://www.ibm.com/developerworks/library/ba-remoteservpi-app/index.html){:new_window}.

## Python

Eine unterstützte Bibliothek für die Arbeit mit {{site.data.keyword.cloudant_short_notm}} unter Verwendung von Python ist [hier ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/python-cloudant){:new_window} verfügbar.

>   **Hinweis:** Python-Anwendungen, die auf {{site.data.keyword.cloudant_short_notm}} zugreifen, haben Komponentenabhängigkeiten. Diese Abhängigkeiten müssen in einer Datei `requirements.txt` angegeben werden. Weitere Informationen finden Sie [hier ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://pip.readthedocs.io/en/1.1/requirements.html){:new_window}.

Laden Sie das aktuelle Bibliotheksrelease [hier ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://pypi.python.org/pypi/cloudant/){:new_window} herunter.
Weitere Informationen zur Python-Sprache finden Sie unter [python.org ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://www.python.org/about/){:new_window}. 

## Swift

Eine unterstützte Bibliothek ist für die Arbeit mit {{site.data.keyword.cloudant_short_notm}} verfügbar.
Die Bibliothek heißt 'Swift{{site.data.keyword.cloudant_short_notm}}' und wird mithilfe
von `cocoapods` installiert.

Der Pod-Datei-Eintrag lautet wie folgt:

```sh
pod 'SwiftCloudant'
```
{:codeblock}

Weitere Informationen zu SwiftCloudant, einschließlich der Details zur Installation und zur Verwendung der Bibliothek für die Speicherung,
Indexierung und Abfrage ferner JSON-Daten unter {{site.data.keyword.cloudant_short_notm}} finden Sie [hier ![Symbol für externen Link](../images/launch-glyph.svg "Symbol für externen Link")](https://github.com/cloudant/swift-cloudant){:new_window}.

Bei der Bibliothek handelt es sich um eine Vorabreleaseversion.
Daher ist momentan keine
vollständige {{site.data.keyword.cloudant_short_notm}}-API-Abdeckung gegeben. 

>   **Hinweis**: SwiftCloudant wird nicht unter iOS unterstützt und Sie können es nicht von Objective-C aufrufen.
