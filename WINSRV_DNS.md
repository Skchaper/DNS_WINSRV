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

#### Créer une zone de recherche directe (domaine --> adresse IP)

Clic droit sur **Zones de recherche directe**, puis ciquer sur **Nouvelle Zone**.
![NOUVELLE_ZONE_1.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/NOUVELLE_ZONE_1.png)

**Suivant** sur l'assistant.
![SUIVANT_2.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/SUIVANT_2.png)

Sélectionner **Zone principale**.
![ZONE_PRINCIPALE_3.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/ZONE_PRINCIPALE_3.png)

Entrer le **Nom de la zone**.
![NOM_ZONE_4.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/NOM_ZONE_4.png)

Cliquer sur **Suivant** en laissant le nouveau fichier nommé tel quel.
![NOM_FICHIER_5.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/NOM_FICHIER_5.png)

Cocher **Ne pas autoriser les mises à jour dynamiques**.
![PAS_AUTORISER_6.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/PAS_AUTORISER_6.png)

Cliquer sur **Terminer**.
![TERMINER_7.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneDirecte/TERMINER_7.png)

#### Créer une zone de recherche inversée (adresse IP --> domaine)

Clic droit sur **Zone de recherche inversée** puis cliquer sur **Nouvelle zone**.
![NOUVELLE_ZONE_1.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/NOUVELLE_ZONE_1.png)

Cliquer sur **Suivant** dans l'assistant.
![SUIVANT_2.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/SUIVANT_2.png)

Sélectionner **Zone principale**.
![ZONE_PRINCIPALE_3.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/ZONE_PRINCIPALE_3.png)

Cliquer sur **Zone de recherche inversée IPv4**.
![ZONE_IPv4_4.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/ZONE_IPv4_4.png)

Entrer l'**ID réseau**.
![ADRESSE_RESEAU_5.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/ADRESSE_RESEAU_5.png)

Pour la zone de recherche, Windows Server crée par défaut un fichier de zone, cliquer sur **Suivant**.
![NOM_FICHIER_6.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/NOM_FICHIER_6.png)

Désactiver les mises à jour en cochant **Ne pas autoriser les mises à jour dynamiques**.
![PAS_AUTORISER_7.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/PAS_AUTORISER_7.png)

Cliquer sur **Terminer**.
![TERMINER_8.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/TERMINER_8.png)

Désormais, nous avons une zone de recherche directe et sa zone de recherche inversée correspondante.
![ZONES_9.png](https://github.com/Skchaper/DNS_WINSRV/blob/main/Screens/ScreensZones/ScreensZoneInvers%C3%A9e/ZONES_9.png)

#### Communication : 2 noms distincts
