# Enquête & Évaluation des Risques
> Ce projet est inspiré par la simulation virtuelle d'emploi en cybersécurité Datacom via [Forage](https://www.theforage.com/simulations/datacom/cybersecurity-zm6d).

## Scénario 1 : Enquête

Dans cette tâche, vous incarnez un consultant en cybersécurité chez XYZ. Un de nos clients, une grande entreprise technologique, a été victime d'une cyberattaque sophistiquée menée par un groupe de menaces persistantes avancées (APT) connu sous le nom d'APT34. Cette attaque, supposée être sponsorisée par un gouvernement étranger, a compromis le réseau de l'organisation, entraînant le vol de données clients précieuses et de propriété intellectuelle.

Votre mission est de mener une recherche initiale sur ce groupe APT34 et d'évaluer l'impact de la violation sur la sécurité de l'information de l'organisation. Mais ne vous inquiétez pas, vous disposerez de tous les outils nécessaires pour comprendre les concepts et principes de la cybersécurité, y compris les menaces, les méthodes d'attaque, et l'importance de la confidentialité, de l'intégrité et de la disponibilité de l'information. De plus, vous serez familiarisé avec les tactiques, techniques et procédures (TTP) d'APT34 ainsi que les vulnérabilités courantes qu'ils exploitent pour accéder aux réseaux.

L'objectif de cette tâche est d'aider notre client à mener une enquête initiale sur APT34 et à évaluer l'impact potentiel de l'attaque sur l'organisation. Vous devrez produire un rapport complet documentant vos conclusions et présentant des recommandations clés pour améliorer la posture de cybersécurité de l'organisation.

En vous plongeant plus profondément dans le monde de la cybersécurité, vous comprendrez le rôle crucial qu'elle joue dans la protection des organisations contre les cybermenaces. Avec la dépendance croissante à la technologie et à Internet, la cybersécurité est devenue un aspect vital des opérations de toute organisation. Il ne s'agit plus de savoir si une organisation sera ciblée, mais plutôt de savoir quand. Cette tâche vous offre une excellente opportunité d'apprendre et d'acquérir une expérience pratique dans le domaine de la cybersécurité tout en ayant un impact positif sur la sécurité de notre client.

## Enquête
Basée sur le [Cadre MITRE ATT&CK](https://attack.mitre.org/) et des outils d'intelligence open-source (OSINT) :

**APT34**

1. Quelle est leur histoire ?  
Le groupe de menaces persistantes avancées (APT) 34, également connu sous les noms OilRig ou HelixKitten, est un groupe de hackers lié à l'Iran et un groupe d'espionnage cybernétique parrainé par l'État, actif depuis 2014.

2. À quel pays/État sont-ils associés ?  
APT34 est associé au gouvernement iranien. Certains experts en cybersécurité pensent qu'ils font partie du Corps des Gardiens de la Révolution Islamique (IRGC), une organisation militaire puissante également impliquée dans les opérations cybernétiques iraniennes.

3. Ciblent-ils des industries spécifiques ?  
Un large éventail d'industries a été ciblé, telles que l'énergie, la finance, les télécommunications et les agences gouvernementales, principalement au Moyen-Orient et aux États-Unis. Ils collectent des informations sensibles et mènent des activités d'espionnage cybernétique pour le compte du gouvernement iranien.

4. Quels sont leurs motifs ?  
Leurs motifs sont liés à l'espionnage. Ils ciblent des informations sensibles telles que la propriété intellectuelle, les données financières et les secrets gouvernementaux. Certaines sources indiquent qu'ils commettent des cybercrimes pour le compte du gouvernement iranien.

5. Quelles sont les tactiques, techniques et procédures (TTP) qu'ils utilisent pour mener leurs attaques ?  
Parmi leurs techniques classiques, mais non limitées à : spear-phishing, ingénierie sociale, distribution de malwares via des sites web malveillants (malwares clients, une porte dérobée appelée POWRUNNER et un système de commande et contrôle personnalisé) et attaques par force brute sur les mots de passe. Une fois qu'ils ont accès au réseau, APT34 essaie d'éviter d'être détecté et de rester dans le système pour lancer une attaque au moment opportun.

6. Quelles mesures de sécurité le client pourrait-il mettre en place pour se défendre contre les cyberattaques menées par cet APT ?  

* Formation des employés : Éduquer les employés sur les cybermenaces les empêchera de tomber dans les pièges des cybercriminels.  
* Authentification multi-facteurs (MFA) : C'est un excellent moyen de protéger l'identité si les hackers parviennent à voler un des identifiants. En mettant en place une authentification multi-facteurs, les attaquants devront trouver plus d'une méthode pour accéder au système.  
* Protection des terminaux : Les antivirus et antimalwares peuvent nous protéger contre les menaces connues.  
* Segmentation du réseau : Segmenter les réseaux en sous-réseaux plus petits pour empêcher la propagation du malware en cas de violation.  
* Plan de réponse aux incidents : Mettre en place un plan de réponse aux incidents pour réagir rapidement en cas de cybermenace.  

## Scénario 2 : Évaluation des Risques

Votre recherche initiale sur le groupe APT est une étape cruciale car elle permet d'identifier les attaquants potentiels, leurs méthodes, motifs et cibles. Comprendre les TTP d'APT34 aide à identifier des vulnérabilités spécifiques et des vecteurs d'attaque qui pourraient être exploités.

Cela a posé une base solide pour la tâche suivante, qui consiste à réaliser une évaluation complète des risques pour le client. Le client dispose d'une clôture autour du périmètre de sa propriété et d'un cadenas à la porte d'entrée pour empêcher l'accès non autorisé. Cependant, l'équipe de direction est préoccupée par les risques et vulnérabilités potentiels qui pourraient compromettre la sécurité de ses informations et systèmes. Ils demandent une évaluation complète des risques pour identifier les menaces potentielles et les vulnérabilités dans leur système ou réseau.

En tant que consultant en cybersécurité, vous comprenez que la réalisation d'une évaluation des risques est un élément essentiel de toute stratégie de cybersécurité efficace. Cela implique d'identifier, d'évaluer et de prioriser les menaces et vulnérabilités potentielles afin de déterminer le niveau de risque et de développer un plan pour atténuer ces risques. Lors de l'évaluation des risques, vous devrez identifier les actifs à protéger, définir la matrice des risques et identifier les scénarios de risques potentiels. Vous évaluerez les niveaux de risque pour chaque scénario, avec et sans les mesures existantes. Enfin, vous fournirez un rapport d'évaluation des risques au client résumant vos conclusions et recommandations pour atténuer les risques et améliorer la posture de sécurité de l'institution.

L'objectif de l'évaluation des risques est d'aider le client à prioriser et à mettre en œuvre des mesures de sécurité appropriées pour atténuer et minimiser les risques. Cela garantira la confidentialité, l'intégrité et la disponibilité de leurs informations et systèmes, ainsi que la protection de leur réputation et de leurs ressources financières. En fin de compte, votre travail aidera le client à se conformer aux exigences réglementaires et légales ainsi qu'aux normes, et à avoir l'esprit tranquille en sachant que leur sécurité est gérée par un expert en cybersécurité compétent et expérimenté.

## Ressources pour l'évaluation des risques
Veuillez consulter ces liens :  
* [NIST](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)  
* [CISA](https://www.cisa.gov/sites/default/files/video/22_1201_safecom_guide_to_cybersecurity_risk_assessment_508-r1.pdf)  
* Autres liens nécessaires.

Les réponses se trouvent dans le fichier joint (`Anis - Evaluation des risques.xlsx`).
