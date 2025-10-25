INSTALACIÓ DE MYSQL EN BINARIS

Primer que res actualitzem per a baixar paquets, i després començarem amb la instalació.

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.001.png)

*Fig 1:Actualització.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.002.png)

*Fig 2: Instalació de libaio.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.003.png)

*Fig 3: Descarreguem des del enllaç.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.004.png)

*Fig 4: Desempaquetem.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.005.png)

*Fig 5: creem enllaç simbòlic i donem permisos.*

Com després de fer proves, no ens ha funcionat per la llibreria “libaio” anem a fer l’instal·lació i configuració a través de “apt-get”.

Abans de començar, fiquem dues targetes de red a cada màquina, on es troben en la mateixa red, en la red interna, i altra NAT per a tindre ixida sense complicacions a internet.

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.006.png)

*Fig 6: IP server*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.007.png)

*Fig 7: IP client.*

Instal·lem el mysql a les dues màquines, en el server instal·larem la que farà de servidor i en l’altra el client.

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.008.png)

*Fig 8: Instal·lació server.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.009.png)

*Fig 9: Estat del servici.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.010.png)

*Fig 10: Comprovació de que les màquines es veuen.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.011.png)

*Fig 11: Comprovació de que les màquines es veuen.*

Ara editarem el fitxer de configuració per tal de ficar l’adreça que es veu en la següent imatge per a poder conectarnos desde altres xarxes i Ips.

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.012.png)

*Fig 12: Fitxer de configuració.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.013.png)

*Fig 13: Reiniciem l’estat per a aplicar canvis.* Seguirem amb les configuracions del mysql per a poder conectarnos des del server.

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.014.png)

*Fig 14: Configuració del usuari.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.015.png)

*Fig 15: Configuració del usuari.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.016.png)

*Fig 16: Comprovem des del client que tenim accés.*

![](Aspose.Words.b48c7879-f6b8-42a8-84bb-d5a56991f581.017.png)

*Fig 17: Instal·lació del workbench.*
