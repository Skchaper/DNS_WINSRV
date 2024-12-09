## WINSRV_DNS

#### Installation du serveur DNS

Pour commencer cliquer sur **Gérer**.
![PANNEAU_GERER_1.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/PANNEAU_GERER_1.png)

Sélectionner **Ajouter des rôles et des fonctionnalités**.
![ONGLET_ROLES_FONCTIONNALITES_2.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ONGLET_ROLES_FONCTIONNALITES_2.png)

Cocher **Installation basée sur un rôle ou une fonctionnaltié**.
![TYPE_INSTALLATION_3.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/TYPE_INSTALLATION_3.png)

Cocher **Serveur DNS** dans la liste.
![ROLES_SERVEUR_4.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ROLES_SERVEUR_4.png)

Cliquer sur **Installer**.
![CONFIRMER_SELECTION_5.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/CONFIRMER_SELECTION_5.png)

Le rôle **Serveur DNS** est installé sur l'Active Directory.

#### Configuration du serveur DNS

Accéder au **Gestionnaire de serveur > DNS**.
![GESTIONNAIRE_DNS_1.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/GESTIONNAIRE_DNS_1.png)
![GESTIONNAIRE_DNS_2.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/GESTIONNAIRE_DNS_2.png)

Clic droit sur le serveur DNS puis cliquer sur **Propriétés**.
![PROPRIETES_3.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/PROPRIETES_3.png)

Séletionner la ou les adresses IP écoutées ou laisser par défaut sur **Toutes les adresses IP**.
![TOUTES_IP_4.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/TOUTES_IP_4.png)

Aller dans l'onglet **Redirecteurs**, cliquer sur **Modifier**.
![MODIFIER_5.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/MODIFIER_5.png)

Renseigner les **Adresses IP**, ici test avec les adresses DNS de Google.
![INDIQUER_ADRESSE_DOMAINE_6.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/INDIQUER_ADRESSE_DOMAINE_6.png)

Enfin, choisir les indications de racine en cas de non configuration ou d'absence de réponse, ici **A.ROOT-SERVERS.NET.**.
![A_ROOT-SERVERS_7.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensConfig/A_ROOT-SERVERS_7.png)


#### Communication : 2 noms distincts
