<p><img src="img/logo.png"><br>Guangzhou Qianhui Information Technology Co., Ltd.</p>
<p>MKS TinyBee V1.0Handbuch<br>Link zum Mainboard-Kauf:<a href="https://www.aliexpress.com/item/1005003640084870.html">https://www.aliexpress.com/item/1005003640084870.html</a><br>
<img src="img/cover.png"></p>
<p></p>
<div class="toc">
 <h3><a name="t0"></a>Artikelverzeichnis</h3>
 <ul><li><a href="#_36" target="_self">I. Produktbeschreibung</a></li><li><ul><li><a href="#11_40" Ziel ="_self">1.1 Funktionen und Vorteile</a></li><li><a href="#12_66" target="_self">1.2 Mainboard-Parameter</a></li><li><a href="#13_71" target="_self">1.3 Schaltplan</a></li><li><a href="#14_81" target="_self">1.4 Abmessungen</a></li > </ul>
  </li><li><a href="#_89" target="_self">Zweitens: Firmware herunterladen, kompilieren, aktualisieren</a></li><li><ul><li><a href= "#21_91" target="_self">2.1-Firmware-Download</a></li><li><a href="#22_97" target="_self">2.2-Firmware-Kompilierung</a></li><li><a href="#23_107" target="_self">2.3-Firmware-Upload</a></li></ul>
  </li><li><a href="#_116" target="_self">Drei, Laufwerksunterteilungseinstellungen</a></li><li><ul><li><a href="# 31_A4988_118 " target="_self">3.1 A4988 Treiberunterteilungseinstellung</a></li><li><a href="#32_TMC2208TMC2209TMC2226_125" target="_self">3.2 TMC2208, TMC2209, TMC2226 Normalmodus-Jumpereinstellung </a ></li><li><a href="#33TMC2225_133" target="_self">3.3 TMC2225-Jumpereinstellungen für Normalmodus</a></li></ul>
  </li><li><a href="#Marlin__145" target="_self">4. Konfiguration der Marlin-Firmware</a></li><li><ul><li><a href="#41__147 " target="_self">4.1 Firmware Basiskonfiguration (erforderlich)</a></li><li><ul><li><a href="#411_149" target="_self">4.1.1 Board Konfiguration </a></li><li><a href="#412__154" target="_self">4.1.2 Konfiguration der seriellen Schnittstelle</a></li><li><a href="# 413__164" target="_self">4.1.3 Bildschirmkonfiguration</a></li><li><a href="#414_sd_208" target="_self">4.1.4 SD-Karte aktivieren</a></li> <li><a href="#415_eeprom_214" target="_self">4.1.5 eeprom aktivieren</a></li><li><a href="#416_LCD_226" target="_self" >4.1.6 LCD-Bildschirm-Spracheinstellung</a></li><li><a href="#417_232" target="_self">4.1.7 Umgebungskonfiguration kompilieren</a></li></ul >
   </li><li><a href="#42_238" target="_self">4.2 Konfiguration der Maschinenparameter (Einstellung gemäß Maschinenparameter)</a></li><li><ul><li><a href="#421__240" target="_self">4.2.1 Konfiguration der Anzahl der Extrusionsköpfe</a></li><li><a href="#422__248" target="_self">4.2.2 Heiß Sensible Typkonfiguration</a></li><li><a href="#423__253" target="_self">4.2.3 Limittypkonfiguration</a></li><li><a href= " #424__258" target="_self">4.2.4 Impulseinstellung</a></li><li><a href="#425__263" target="_self">4.2.5 Nullrichtungseinstellung</a></li><li><a href="#426__268" target="_self">4.2.6 Bereichseinstellungen der Druckplattform</a></li><li><a href="#427_271" target="_self ">4.2.7 Motorrichtungseinstellung</a></li></ul>
   </li><li><a href="#43_277" target="_self">4.3 Erweiterte Konfiguration</a></li><li><ul><li><a href="#431__279" target ="_self">4.3.1 Neustart nach Stromausfall</a></li><li><a href="#432__286" target="_self">4.3.2 Materialbrucherkennung</a></li ><li><a href="#433_wifi_312" target="_self">4.3.3 WLAN-Konfiguration</a></li></ul>
  </li></ul>
  </li><li><a href="#3dtouch_342" target="_self">5. Automatische 3dtouch-Nivellierungsfunktion</a></li><li><ul><li><a href=" #51_344" target="_self">5.1 Sensor-Triggerpegel einstellen</a></li><li><a href="#52pin_349" target="_self">5.2 Sensorsignal-Pin einstellen</a></li><li><a href="#53_BLTOUCH_363" target="_self">5.3 BLTOUCH aktivieren</a></li><li><a href="#54_367" target="_self">5.4 Festlegen der Versatz zwischen Sonde und Extrusionskopf</a></li><li><a href="#55_372" target="_self">5.5 Stellen Sie den Abstand zwischen dem Sensor und der Kante der Druckplattform beim Nivellieren ein</a></li><li><a href="#56__378" target="_self">5.6 Automatische Ausrichtung aktivieren</a></li><li><a href="#57__383" Ziel = "_self">5.7 Nivellierungsrasterpunkte setzen</a></li><li><a href="#58__390" target="_self">5.8 Servo aktivieren</a></li><li><a href="#59__396" target="_self">5.9 Auto-Leveling-Datenaufrufcode hinzufügen</a></li><li><a href="#510_z_safe_homing__407" target="_self">5.10 z_safe_homing-Konfiguration</a></li></ul>
  </li><li><a href="#WEB_411" target="_self">Sechs, Konfiguration der WEB-Verbindung</a></li><li><a href="#FAQ_460" target="_self" >7. FAQ</a></li></ul>
</div>
<p></p>
<p>Maker Base QQ-Gruppe: 489095605 232237692<br> E-Mail: Huangkaida@makerbase.com.cn</p>
<h1><a name="t1"></a><a id="_36"></a>I. Produktbeschreibung</h1>
<p>Das MKS TinyBee V1.0-Mainboard ist eine 32-Bit-Hauptsteuerplatine, die von Maker Base eingeführt wurde, um die Marktnachfrage zu befriedigen.Das Mainboard unterstützt die WLAN-Funktion ohne zusätzliches WLAN-Modul, unterstützt die Webseitensteuerung, unterstützt LCD2004, LCD mini12864, MKS mini12864 V3 .0, LCD12864, unterstützt die serielle Bildschirmsteuerung. </p>
<h2><a name="t2"></a><a id="11_40"></a>1.1 Funktionen und Vorteile</h2>
<p>1. Unterstützung der WLAN-Steuerung und Übertragung von Dateien;<br> 2. Die Treiberunterteilung ist auf die Wähleinstellung eingestellt, die für die Treiberunterteilungseinstellung bequemer ist;<br> 3. Die Hauptplatinenplatine nimmt das Immersionsgold an Prozess, der eine bessere Stabilität hat <br> 3. Benutzer können den Motorantrieb selbst ersetzen, unterstützen 4988, 8825, 8729, TMC2208, TMC2209, TMC2225, TMC2226; <br> 4. Reservieren Sie externe Antriebssignale, die angeschlossen werden können externe große Laufwerke zum Antrieb von 57, 86 Motoren ;<br> 5. Verwendung hochwertiger MOSFETs, bessere Wärmeableitung, Gewährleistung der Langzeitstabilität; ;<br> 7. Die stabile und zuverlässige Filterschaltung reduziert die Möglichkeit von Störungen erheblich, und vermeidet so weit wie möglich das Phänomen des Absturzes und Herumlaufens im Druckprozess;<br> 8. Verwendung des seriellen CH340-Port-Chips unter der Prämisse, Stabilität und Zuverlässigkeit zu gewährleisten. Dies reduziert die Kosten und löst das Problem des vorherigen 16U2-Treibers war schwierig zu installieren;<br> 9. Verwenden Sie die Open-Source-Firmware Marlin2.0.X-Firmware;<br> 10. Unterstützt LCD2004, LCD12864, MKS MINI12864 V1.0, MKS MINI12864 V3.0, unterstützt TFT24, TFT28, TFT32, TFT35, H43-Touchscreen, entwickelt von Maker;<br> 11. XYZ-Achsen verwenden Klemmen in verschiedenen Farben, um dem Motor und Endschalter zu entsprechen, was für die Verkabelung praktisch ist;<br> 12. Unterstützung von 3dtouch;<br> 13. Onboard TF-Kartenhalter, stabilerer Offline-Druck;</p>
<h2><a name="t3"></a><a id="12_66"></a>1.2 Motherboard-Parameter</h2>
<p><img src="img/1.png"></p>
<h2><a name="t4"></a><a id="13_71"></a>1.3 Schaltplan</h2>
<p><img src="img/2.png"></p> 
<h2><a name="t5"></a><a id="14_81"></a>Zeichnung der Größe 1,4</h2>
<p>Motherboard-Größentabelle:<br> <img src="img/3.png"></p>
<h1><a name="t6"></a><a id="_89"></a>Zweitens Firmware herunterladen, kompilieren, aktualisieren</h1>
<h2><a name="t7"></a><a id="21_91"></a>2.1-Firmware-Download</h2>
<p>MKS TinyBee V1.0-Firmware-Download-Link:<br> <a href="https://github.com/makerbase-mks/MKS-TinyBee">https://github.com/makerbase-mks/MKS-TinyBee</a></p>
<h2><a name="t8"></a><a id="22_97"></a>2.2-Firmware-Kompilierung</h2>
<p>Firmware-Kompilierung erfordert VScode, VScode-Installations-Tutorial-Link:<br> <a href="https://www.bilibili.com/video/BV1XK4y1C7k5">https://www.bilibili.com/video/BV1XK4y1C7k5</a></p>
<p>Firmware-Kompilierung:<br> Nachdem die Firmware-Konfiguration abgeschlossen ist, klicken Sie auf "✔" in der unteren linken Ecke der VScode-Seite, um mit der Kompilierung zu beginnen. <br> <img src="img/4.png"></p>
<h2><a name="t9"></a><a id="23_107"></a>Upload der 2.3-Firmware</h2>
<p>Klicken Sie nach dem Kompilieren der Firmware auf „→“ in der unteren linken Ecke der VScode-Seite, um mit dem Hochladen der Firmware zu beginnen. </p>
<p><img src="img/5.png"></p>
<h1><a name="t10"></a><a id="_116"></a>Drittens die Unterteilungseinstellungen für Fahrer</h1>
<h2><a name="t11"></a><a id="31_A4988_118"></a>3.1 A4988-Treiberunterteilungseinstellungen</h2>
<p>A4988 Treiber-Unterteilungseinstellung, die drei Zifferblätter unterhalb des Treibers werden bis zu 16 Unterteilungen angewählt, wie in der folgenden Abbildung gezeigt (X-Achse als Beispiel):</p>
<p><img src="img/6.png"></p>
<h2><a name="t12"></a><a id="32_TMC2208TMC2209TMC2226_125"></a>3.2 TMC2208, TMC2209, TMC2226 Normalmodus-Jumpereinstellungen</h2>
<p>Die drei Zifferblätter an der Unterseite der TMC2208-, TMC2209- und TMC2226-Treiber sind 16 Unterteilungen, wenn sie angewählt sind, wie in der Abbildung unten gezeigt (X-Achse als Beispiel):</p>
<p><img src="img/7.png"></p>
<h2><a name="t13"></a><a id="33TMC2225_133"></a>3.3 TMC2225-Jumpereinstellungen für Normalmodus</h2>
<p>Unterteilungseinstellungen des TMC2225-Treibers, die zweite Skala unter dem Treiber ist angewählt, die erste und dritte Skala sind 16 Unterteilungen, wie in der folgenden Abbildung gezeigt (X-Achse als Beispiel):</p>
<p><img src="img/8.png"></p>
<h1><a name="t14"></a><a id="Marlin__145"></a>Viertens: Konfiguration der Marlin-Firmware</h1>
<h2><a name="t15"></a><a id="41__147"></a>4.1 Firmware-Basiskonfiguration (erforderlich)</h2>
<h3><a name="t16"></a><a id="411_149"></a>4.1.1 Platinenkonfiguration</h3>
<p>Konfigurieren Sie das Board als BOARD_MKS_TINYBEE in der Datei configuration.h<br> <img src="img/9.png"></p>
<h3><a name="t17"></a><a id="412__154"></a>4.1.2 Konfiguration der seriellen Schnittstelle</h3>
<p>Setzen Sie den ersten seriellen Port in der Datei configuration.h auf 0, der Konfigurationsfehler führt dazu, dass das Motherboard keine Verbindung zum Computer herstellen kann; der zweite serielle Port ist auf -1 konfiguriert, die Konfigurationsfehler-Webseite wird dies nicht tun in der Lage sein, die Temperaturinformationen des Motherboards zu erhalten; Dann sind die Baudraten alle auf 115200 eingestellt. </p>
<p><img src="img/10.png"></p><p><img src="img/11.png"></p>
<h3><a name="t18"></a><a id="413__164"></a>4.1.3 Bildschirmkonfiguration</h3>
<p><strong>(Hinweis: Der LCD-Bildschirm kann nur einen der folgenden Bildschirme aktivieren, und das gleichzeitige Aktivieren von mehr als einem führt zu Kompilierungsfehlern)</strong><br> 1. LCD 2004-Konfiguration, in der Konfiguration Datei aktivieren</p>
<h3><a name="t18"></a><a id="413__164"></a>4.1.3 Bildschirmkonfiguration</h3>
<p><strong>(Hinweis: Der LCD-Bildschirm kann nur einen der folgenden Bildschirme aktivieren, und das gleichzeitige Aktivieren von mehr als einem führt zu Kompilierungsfehlern)</strong><br> 1. LCD 2004-Konfiguration, in der Konfiguration Datei aktivieren</p>
<p>#define REPRAP_DISCOUNT_SMART_CONTROLLER</p>
<p><img src="img/12.png"></p>
<p>2, LCD12864-Bildschirmkonfiguration, in der Konfigurationsdatei aktivieren</p>
<p>#define REPRAP_DISCOUNT_FULL_GRAPHIC_SMART_CONTROLLER</p>
<p><img src="img/13.png"></p>
<p>3. MKS MINI12864 V1.0 Bildschirmkonfiguration</p>
<p>In Konfigurationsdatei aktivieren</p>
<p>#define MKS_MINI_12864</p>
<p><img src="img/14.png"></p>
<p>4. MKS MINI12864 V3.0 Bildschirmkonfiguration</p>
<p>Aktiviere #define MKS MINI12864 V3 in der Konfigurationsdatei</p>
<p><img src="img/15.png"></p>
<h3><a name="t19"></a><a id="414_sd_208"></a>4.1.4 SD-Karte aktivieren</h3>
<p>Aktivieren Sie <code>#define SDSUPPORT</code><br> in der Konfigurationsdatei</p><p> <img src="img/16.png"></p>
<h3><a name="t20"></a><a id="415_eeprom_214"></a>4.1.5 EEPROM aktivieren</h3>
<p>In Konfigurationsdatei aktivieren</p>
<p>#define EEPROM_SETTINGS</p>
<p><img src="img/17.png"></p>
<h3><a name="t21"></a><a id="416_LCD_226"></a>4.1.6 Spracheinstellung des LCD-Bildschirms</h3>
<p>Setzen Sie die Sprache in der Konfigurationsdatei auf zh_CN für Chinesisch, die Voreinstellung ist Englisch. </p>
<p><img src="img/18.png"></p>
<h3><a name="t22"></a><a id="417_232"></a>4.1.7 Konfiguration der Kompilierungsumgebung</h3>
<p>Konfigurieren Sie die Kompilierungsumgebung als mks_tinybee in der Datei paltformio.ini</p>
<p><img src="img/19.png"></p>
<h2><a name="t23"></a><a id="42_238"></a>4.2 Konfiguration der Maschinenparameter (gemäß Maschinenparameter eingestellt)</h2>
<h3><a name="t24"></a><a id="421__240"></a>4.2.1 Konfiguration der Anzahl der Extrusionsköpfe</h3>
<p>MKS TinyBee V1.0 unterstützt bis zu 2 Extrusionsköpfe bei Verwendung von Dual-ExtrusionWenn Sie ausgehen, müssen Sie die thermischen und SD-Kartenerkennungs-Pin-Jumper des Thermoextruders 2 auf der Hauptplatine rechts einstecken. <br> <img src="img/20.png"></p>
<h3><a name="t25"></a><a id="422__248"></a>4.2.2 Thermische Konfiguration</h3>
<p>MKS TinyBee V1.0 Motherboard unterstützt nur 100K Thermal, #define TEMP_SENSOR_0 ist Extrusionskopf 1, #define TEMP_SENSOR_1 ist Extrusionskopf 2, #define TEMP_SENSOR_BED ist heißes Bett<br> <img src="img/21.png">
<h3><a name="t26"></a><a id="423__253"></a>4.2.3 Konfiguration des Grenzwerttyps</h3>
<p>Konfiguration des Endschaltertyps (wahr/falsch), wahr ist ein normalerweise offener Schalter, falsch ist ein normalerweise geschlossener Schalter. <br> <img src="img/22.png"></p>
<h3><a name="t27"></a><a id="424__258"></a>4.2.4 Pulseinstellungen</h3>
<p>#define DEFAULT_AXIS_STEPS_PER_UNIT {80, 80, 400, 93} in der Konfigurationsdatei wird verwendet, um die Impulse der X-, Y-, Z- bzw. E-Achse einzustellen.Der Impulswert muss entsprechend dem tatsächlichen Wert berechnet und eingestellt werden Zustand der Maschine. <br> <img src="img/23.png"></p>
<h3><a name="t28"></a><a id="425__263"></a>4.2.5 Nullrichtungseinstellung</h3>
<p>Stellen Sie die Nullungsrichtung in der Konfigurationsdatei ein, -1 ist die minimale Richtung, 1 ist die maximale Richtung<br> <img src="img/24.png"></p>
<h3><a name="t29"></a><a id="426__268"></a>4.2.6 Bereichseinstellungen der Druckplattform</h3>
<p><img src="img/25.png"></p>
<h3><a name="t30"></a><a id="427_271"></a>4.2.7 Motorrichtungseinstellung</h3>
<p>Die Einstellung der Motorrichtung, falsch und wahr, stellen die beiden Drehrichtungen dar, wenn die Bewegungsrichtung entgegengesetzt ist, kann die entgegengesetzte Konfiguration vorgenommen werden. </p>
<p><img src="img/26.png"></p>
<h2><a name="t31"></a><a id="43_277"></a>4.3 Erweiterte Konfiguration</h2>
<h3><a name="t32"></a><a id="431__279"></a>4.3.1 Neustart nach Stromausfall</h3>
<p>Aktivieren Sie in der erweiterten Konfigurationsdatei configuration_adv.h<br> #define POWER_LOSS_RECOVERY und ändern Sie #define PLR_ENABLED_DEFAULT false in<br> #define PLR_ENABLED_DEFAULT true<br> <img src="img/28.png"></p>
<h3><a name="t33"></a><a id="432__286"></a>4.3.2 Materialbrucherkennung</h3>
<p>Aktivieren Sie #define FILAMENT_RUNOUT_SENSOR in der Konfigurationsdatei<br> <img src="img/29.png"></p>
<p>Stellen Sie den Pegel des Unterbrechungserkennungsschalters in der Konfigurationsdatei ein (LOW/HIGH)</p>
<p><img src="img/30.png"></p>
<p>Aktiviere #define NOZZLE_PARK_FEATURE in der Konfigurationsdatei</p>
<p><img src="img/31.png"></p>
<p>Aktiviere #define ADVANCED_PAUSE_FEATURE im erweiterten Profil</p>
<p><img src="img/33.png"></p>
<p>Aktiviere #define PARK_HEAD_ON_PAUSE in der erweiterten Konfigurationsdatei</p>
<p><img src="img/34.png"></p>
<h3><a name="t34"></a><a id="433_wifi_312"></a>4.3.3 WLAN-Konfiguration</h3>
<p>Aktivieren Sie #define ESP3D_WIFISUPPORT und #define WEBSUPPORT, #define OTASUPPORT, #define WIFI_CUSTOM_COMMAND in der erweiterten Konfigurationsdatei</p>
<p><img src="img/35.png"></p>
<h1><a name="t35"></a><a id="3dtouch_342"></a>5. Automatische 3dtouch-Nivellierungsfunktion</h1>
<h2><a name="t36"></a><a id="51_344"></a>5.1 Sensorauslösepegel einstellen</h2>
<p>Die Stufe von 3dtouch ist auf „false“ gesetzt<br> <img src="img/36.png"></p>
<h2><a name="t37"></a><a id="52pin_349"></a>5.2 Sensorsignal-Pin einstellen</h2>
<p>Da auf der Hauptplatine nur eine z_min-Grenzschnittstelle vorhanden ist, muss z_safe_homing aktiviert werden, um die automatische Nivellierung von 3Dtouch zu verwenden (Hinweis: Die 3Dtouch-Signalsteuerleitung ist eine 2-polige Leitung, eine schwarze und eine weiße Leitung, die weiße Leitung ist die Signalleitung, verbunden mit Z_min limit S end). </p>
<p><img src="img/37.png"></p>
<h2><a name="t38"></a><a id="53_BLTOUCH_363"></a>5.3 BLTOUCH aktivieren</h2>
<p><img src="img/38.png"></p>
<h2><a name="t39"></a><a id="54_367"></a>5.4 Einstellen des Versatzes zwischen Sonde und Extrusionskopf</h2>
<p> sind die Offsets der X-, Y- bzw. Z-Achse. Die Offsets von X und Y müssen entsprechend der tatsächlichen Messung ausgefüllt werden. Z_offset kann nach der Nivellierung angepasst werden. <br> <img src="img/39.png"></p>
<h2><a name="t40"></a><a id="55_372"></a>5.5 Stellen Sie den Abstand zwischen dem Sensor und der Kante der Druckplattform beim Nivellieren ein</h2>
<p>Der Wert ist standardmäßig 10 (Hinweis: Der Wert kann nicht zu klein eingestellt werden, ein zu kleiner Wert führt dazu, dass der Sensor die Plattformreichweite während des Nivellierens überschreitet, was zu einem Nivellierungsfehler führt)<br> <img src="img/40.png">
<h2><a name="t41"></a><a id="56__378"></a>5.6 Auto-Level aktivieren</h2>
<p>Aktivieren Sie die lineare automatische Ausrichtung in der Konfigurationsdatei<br> <img src="img/41.png"></p>
<h2><a name="t42"></a><a id="57__383"></a>5.7 Nivellierungsrasterpunkte festlegen</h2>
<p>Stellen Sie die Anzahl der Nivellierungspunkte in der Konfigurationsdatei ein, der Standardwert ist 3*3 Punkte</p>
<p><img src="img/42.png"></p>
<h2><a name="t43"></a><a id="58__390"></a>5.8 Servo aktivieren</h2>
<p>Servos in der Konfigurationsdatei aktivieren #define NUM_SERVOS 1<br> <img src="img/43.png"></p>
<h2><a name="t44"></a><a id="59__396"></a>5.9 Auto-Leveling-Datenaufrufcode hinzufügen</h2>
<p>set_bed_leveling_enabled(true) in G28.cpp-Datei hinzufügen;</p>
<p><img src="img/44.png"></p>
<h2><a name="t45"></a><a id="510_z_safe_homing__407"></a>5.10 z_safe_homing-Konfiguration</h2>
<p><img src="img/45.png"></p>
<h1><a name="t46"></a><a id="WEB_411"></a> Sechs, WEB-Verbindungskonfiguration</h1>
<p>Die Firmware aktiviert WLAN. Nachdem das Motherboard aktualisiert wurde, ist das Standard-WLAN der AP-Modus (Local Area Network). Verwenden Sie dann den Computer oder das Mobiltelefon, um die WLAN-Liste anzuzeigen. Sie können sehen, dass der Name des WLANs marlin_esp lautet . </p>
<p><img src="img/46.png"></p>
<p>Geben Sie das Passwort ein, um eine WLAN-Verbindung herzustellen (das standardmäßige WLAN-Passwort lautet 12345678);<br> <img src="img/47.png"></p>
<p>Öffnen Sie dann den Browser und geben Sie die IP-Adresse ein, um die Weboberfläche aufzurufen (die Standard-IP-Adresse ist 192.168.0.1);</p>
<p><img src="img/48.png"></p>
<p>Klicken Sie dann zum Hochladen der Datei der Websteuerungsschnittstelle auf den Link zum Herunterladen der Datei: <a href="https://github.com/luc-github/ESP3DLib">https://github.com/luc-github/ESP3DLib</a></p>
<p><img src="img/49.png"></p>
<p><img src="img/50.png"></p>
<p><img src="img/51.png"></p>
<p>Überprüfen Sie nach dem Hochladen die Aktualisierungszeit auf der Webseite, und Sie können die Steuerung starten, wenn Sie die Temperatur sehen</p>
<p><img src="img/52.png"></p>
<p>STA-Modus-Einstellung, ESP3D-Schnittstelle aufrufen, wählen Sie dann Client Station, geben Sie den Namen und das Passwort des WLANs ein, mit dem Sie sich verbinden möchten, überprüfen Sie die Einstellungen und starten Sie das Motherboard neu. Wenn es sich um ein LCD handelt, können Sie die zugewiesene IP auf der LCD-Oberfläche anzeigen. Wenn Sie einen seriellen Anschlussbildschirm oder keinen Bildschirm verwenden, müssen Sie sich auf der Verwaltungsseite des Routers anmelden, um die IP anzuzeigen, und dann die IP erneut eingeben den Browser, um die Webseite aufzurufen. </p>
<p><img src="img/53.png"></p>
<p>7. Technischer Support und Garantie<br>  Einschalttest wird vor der Lieferung durchgeführt, um sicherzustellen, dass es vor der Lieferung offiziell verwendet werden kann. <br>  Willkommen Freunde zur Teilnahme an der Diskussionsgruppe: 232237692<br>  Willkommen zur Blog-Kommunikation: https://blog.csdn.net/gjy_skyblue<br>  3D-Drucker-Motherboard-Anpassung, kontaktieren Sie Huang Sheng: 13148932315 Tan Sheng: 15521395023 Peng Sheng: 13427595835<br>  Wenn Sie Fragen haben, wenden Sie sich bitte an unseren Kundenservice oder finden Sie technische Supportmitarbeiter in der Gruppe, wir werden Ihnen von ganzem Herzen zur Verfügung stehen</p>
<p><img src="img/qr1.png"></p>
<p><img src="img/qr2.png"></p>

<h1><a name="t47"></a><a id="FAQ_460"></a> Sieben, häufig gestellte Fragen</h1>
<p>1. Was soll ich tun, wenn das Motherboard die Firmware nicht aktualisieren kann? <br> Antwort: Überprüfen Sie, ob der Computer den COM-Port des Motherboards erkennt, der Gerätemanager des Computers kann den COM-Port des CH340 sehen; <br> Wenn das Motherboard zu stark belastet wurde, wird davon abgeraten Verwenden Sie USB, um das Motherboard mit Strom zu versorgen Um die Firmware zu aktualisieren, kann es leicht vorkommen, dass die Firmware aufgrund unzureichender Stromversorgung nicht aktualisiert werden kann; <br> Das Motherboard kann nicht mit dem seriellen Bildschirm verbunden werden, während es mit dem Computer verbunden ist, um die Firmware zu aktualisieren, und Der serielle Bildschirm muss getrennt werden. </p>
<p>2. Nach der Aktualisierung der Firmware sind der angezeigte Puls, die maximale Geschwindigkeit und andere auf dem LCD-Bildschirm angezeigte Parameter falsch. Was tun?<br> Antwort: Rufen Sie die erweiterte Einstellungsschnittstelle auf dem Bildschirm auf, initialisieren Sie dann das Eeprom Zurück zur Einstellungsoberfläche, Daten speichern, Daten laden</p>
<p>3. Was soll ich tun, wenn das Motherboard nicht mit dem Host-Computer des Computers verbunden werden kann? <br> Antwort: Bestätigen Sie, ob die serielle Schnittstelle des Motherboards in der Konfigurationsdatei korrekt ist, MKS Tibybee verwendet die serielle Schnittstelle 0; <br> Nachdem das Motherboard mit dem Computer verbunden ist, rufen Sie den Geräte-Manager auf, um zu überprüfen, ob der Computer die erkennt COM-Port des Motherboards, wenn ja, können Sie den Host-Computer neu starten, die vom Host-Computer eingestellte Baudrate muss mit der Einstellung der Konfigurationsdatei übereinstimmen; wenn sie nicht erkannt wird, überprüfen Sie, ob die USB-Verbindung einen schlechten Kontakt hat. </p>
<p>4. Was soll ich tun, wenn der automatische Nivellierungseffekt von 3Dtouch nicht gut ist? <br> Antwort: ⭐Die Anzahl der Nivellierungspunkte kann erhöht werden;<br>⭐Das #define MULTIPLE_PROBING 2 kann in der Konfigurationsdatei aktiviert werden, und das Nivellieren kann an jedem Punkt wiederholt werden, um einen Mittelwert mit höherer Genauigkeit zu erhalten; <br>⭐Automatisch umschaltbar Der Weg zum Nivellieren, #define AUTO_BED_LEVELING_LINEAR eignet sich für Plattformen mit geneigter Ebene<br> #define AUTO_BED_LEVELING_BILINEAR eignet sich für gekrümmte unebene Plattformen und große Plattformen. </p>
<p>5. Wie gehe ich mit dem Ausfall der automatischen Nivellierung um? <br> Es gibt viele Gründe, warum die automatische Ausrichtung fehlschlägt, wir haben ein Video darüber gemacht, siehe den Link für Details:</p>
<p><a href="https://www.bilibili.com/video/BV1ZB4y1P7LZ?from=search&amp;seid=12028097711066543268">https://www.bilibili.com/video/BV1ZB4y1P7LZ?from=search&amp;seid=12028097711066543268</a></p>
