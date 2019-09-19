

# Focus : la gendarmerie nationale et le logiciel libre

Un exemple d'une migration à grande échelle réussie vers le logiciel libre est celui de gendarmerie nationale.

Le lieutenant-colonel Stéphane Dumond, chef de bureau IT du Service des Technologies et des Systèmes d'Information de la Sécurité Intérieure (ST(SI)²), était l'invité de l'émission de l'April « Libre à vous ! » sur la radio Cause Commune. Stéphane Dumond a notamment conduit le projet d'industrialisation de la migration vers un système libre sur le poste de travail des gendarmes. Dans l'émission il a raconté l'histoire de la migration et expliqué les conditions de son succès.

-   Le podcast (55 minutes) est disponible sur <https://april.org/libre-a-vous-diffusee-mardi-3-septembre-2019-sur-radio-cause-commune>

-   « Libre à vous ! » <https://april.org/libre-a-vous>

-   radio Cause Commune <https://cause-commune.fm/>


# LemonLDAP::NG : le SSO de l'administration

[LemonLDAP::NG](https://lemonldap-ng.org/welcome/) est un [Web-SSO](https://fr.wikipedia.org/wiki/Authentification_unique) largement diffusé en France. Il implémente de nombreux protocoles de fédération d'identité parmi lesquels : [SAML](https://fr.wikipedia.org/wiki/Security_assertion_markup_language), [CAS](https://fr.wikipedia.org/wiki/Central_Authentication_Service) et [OpenID-Connect](https://fr.wikipedia.org/wiki/OpenID_Connect) dont l'implémentation a été qualifiée fournisseur d'identité ou de service pour [FranceConnect](https://fr.wikipedia.org/wiki/FranceConnect).

Presque tous les ministères français l'utilisent, ainsi que de nombreuses collectivités territoriales.

Aux environs de l'année 2002, parallèlement la gendarmerie et le ministère des finances décident de déployer un SSO. Ce dernier développe un logiciel libre simple pour cet usage : LemonLDAP. La gendarmerie ayant des besoins plus complexes adopte dans un premier temps un logiciel propriétaire mais abandonne cette idée devant le coût et le manque de souplesse. Elle reprend alors le code initial de LemonLDAP et le réécrit pour ses usages. En 2005, la première version complète est publiée en open-source.

Sous financement public initialement, la société Linagora entre dans la communauté LemonLDAP::NG vers 2006. LemonLDAP::NG se diffuse progressivement dans la plupart des administrations, faisant ainsi réaliser plusieurs dizaines de millions d'euros d'économies par an en comparaison avec la solution de [Forgerock](https://www.forgerock.com/platform/access-management/sso), leader du marché.

La communauté LemonLDAP::NG est toujours très active, hébergée par la [fondation OW2](https://www.ow2.org/), associant plusieurs entreprises et le [ST(SI)²](https://fr.wikipedia.org/wiki/Service_des_technologies_et_des_syst%C3%A8mes_d%27information_de_la_S%C3%A9curit%C3%A9_int%C3%A9rieure), et a sorti en 2019 son implémentation du [SSO-as-a-Service](https://lemonldap-ng.org/documentation/2.0/ssoaas).  Aujourd'hui, c'est [Worteks](https://www.worteks.com/fr/) qui contribue principalement aux côtés su ST(SI)², à la fois via des financements des clients (dont [Orange](https://www.orange.fr)), mais aussi sur des jours de R&D internes.


# Aide : un questionnaire de EU FOSSA 2 sur l'open source

[EU FOSSA 2](https://ec.europa.eu/info/departments/informatics/eu-fossa-2_en) est une initative de la commission européenne pour soutenir des logiciels libres critiques.  Elle a été lancée sur l'impulsion du Parlement européen après la découverte de bug de sécurité Heartbleed en 2014.

EU FOSSA 2 lance un questionnaire en anglais autour de l'open source.  Cela vous prendra dix minutes environ : [voir le questionnaire](https://ec.europa.eu/eusurvey/runner/EUFOSSA2-Survey).


# Nouveaux outils libres pour l'administration

-   Annonce de <https://xxx.numerique.gouv.fr>
-   Annonce de yunohost.studio.etalab/xxx ?


# Publication de code source

-   Cloudwatt a publié son intégration de [TungstenFabric](https://github.com/cloudwatt/nixpkgs-tungsten), le composant SDN de son offre IaaS.  Cette intégration est basée sur Nix et publiée sous licence MIT.  Plus de détails dans l'article de blog <https://dev.cloudwatt.com/en/blog/introducing-nixpkgs-tungsten.html>

-   Les Pays de la Loire [publient](https://www.data.gouv.fr/fr/reuses/pays-de-la-loire-publication-dune-nouvelle-application-sur-les-energies-renouvelables/) une nouvelle application libre sur les énergies renouvelables.

-   [CARTElette](https://www.data.gouv.fr/fr/reuses/cartelette-creation-de-couches-cartographiques-a-partir-du-code-officiel-geographique-cog-et-des-couches-ign/) : Création de couches cartographiques à partir du code officiel géographique (COG) et des couches IGN (voir sur [GitHub](https://github.com/antuki/CARTElette)).


# Nouvelles présentations sur #bluehats

-   <https://speakerdeck.com/bluehats/demarche-apisation>
-   <https://speakerdeck.com/bluehats/codes-sources-des-organismes-publics>
-   <https://speakerdeck.com/bluehats/presentation-detalab>
-   <https://speakerdeck.com/bluehats/building-free-software-bridges-between-public-agencies-and-citizens>


# Open Fisca obtient un prix « Share & Reuse »

La Commission européenne a dévoilé le 11 juin le palmarès de ses « Sharing and Reuse Awards » (prix « Partage et Réutilisation »).  Ce concours récompense les logiciels libres et services informatiques partagés mis au point par ou pour une administration publique et réutilisés par d’autres administrations.

Pour la deuxième édition du concours, la direction interministérielle du numérique et du SI de l’État français (DINSIC) s’est vu décerner le prix du logiciel open source le plus innovant pour [Open Fisca](https://openfisca.org/en/), la plateforme libre et ouverte qui rend le système social et fiscal calculable.

Initié par France Stratégie en 2011, OpenFisca a été développé par la DINSIC, en particulier par ses missions Etalab et beta.gouv.fr, en collaboration avec l’institut des politiques publiques, la direction de la Sécurité sociale et l’Assemblée nationale.  Collaboratif, OpenFisca repose actuellement sur une communauté internationale de plus de 70 personnes qui chaque jour contribuent, s’entraident et participent à en améliorer le code.  Onze pays dans le monde l’utilisent actuellement.


# Événements


## À venir

-   Sprint open source #bluehats


## Passés

-   OpenStreetMap France : Les 14-15-16 juin 2019, durant 3 jours, contributeurs, utilisateurs, représentants de collectivités et d'entreprises gravitant autour du Web et de l'information géographique, chercheurs, mais aussi personnes curieuses de découvrir cette « carte libre du monde » que représente OpenStreetMap, se retrouveront pour partager leurs expériences, se tenir informé, se former, découvrir l'écosystème et les multiples applications - existantes ou à imaginer – autour d'OpenStreetMap.  <https://sotm2019.openstreetmap.fr/> pour le programme et le déroulé Et plus tard <https://openstreetmap.fr> et <https://peertube.openstreetmap.fr/>


# Brèves

-   La mission [Etalab](https://www.etalab.gouv.fr/) a réactivé son canal IRL pour permettre à tout le monde d'échanger avec l'équipe technique : rendez-vous soit sur le canal #Etalab sur un serveur irc.freenode.net, soit sur [riot](https://riot.im/app/#/room/#freenode_#etalab:matrix.org).

-   La licence CeCiLL v2.1, figurant parmi les [licences homologuées](https://www.data.gouv.fr/fr/licences) lorsqu'une administration veut publier du code source, est entrée dans la liste.  Cette licence a intégré la liste des licences présentées par [choosealicense.com](https://choosealicense.com) - voir sa description [ici](https://choosealicense.com/licenses/cecill-2.1/) et [ce tableau comparatif](https://choosealicense.com/appendix/) de l'ensemble des licences libres.

-   L'initiative <https://publiccode.net> propose des ressources pour aider les organismes publics à créer et maintenir des logiciels libres.


# Revue de presse

-   [La gendarmerie et les logiciels libres, pour l'émission de rentrée de "Libre à vous !"](https://www.zdnet.fr/blogs/l-esprit-libre/la-gendarmerie-et-les-logiciels-libres-pour-l-emission-de-rentree-de-libre-a-vous-39889841.htm) (<https://www.zdnet.fr>)
-   [Le CERN délaisse Microsoft pour le logiciel libre](https://www.zdnet.fr/actualites/le-cern-delaisse-microsoft-pour-le-logiciel-libre-39885945.htm) (<https://www.zdnet.fr>)
-   [Budget participatif : la mairie choisit l’open source](https://lagazette-ladefense.fr/2019/06/19/budget-participatif-la-mairie-choisit-lopen-source/) (<https://lagazette-ladefense.fr>)
-   [[Tribune] Contrat, parasitisme et logiciel libre](https://www.usine-digitale.fr/article/tribune-contrat-parasitisme-et-logiciel-libre.N871845) (<https://www.usine-digitale.fr>)
-   Un nouveau guide sur l'[open source en entreprise](https://aws.amazon.com/fr/opensource/enterprise-oss-book/) (<https://aws.amazon.com>)
-   [Jean-Séverin Lair (DINSIC) : « Tout le monde est concerné par l'archivage »](https://www.cio-online.com/actualites/lire-jean-severin-lair-dinsic-%C2%A0-%C2%A0tout-le-monde-est-concerne-par-l-archivage%C2%A0-11301.html) (<https://www.cio-online.com>)

