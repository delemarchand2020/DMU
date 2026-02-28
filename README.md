# Projet DMU (Développement en Milieu Utilisateur)

## Contexte

Un **DMU** signifie *Développement en Milieu Utilisateur*.

En entreprise, on distingue principalement deux groupes :
- **Les Affaires** (le métier)
- **Les TI** (les Technologies de l'Information)

Le rôle des TI est de livrer des solutions informatiques aux affaires. 

### La livraison de solutions traditionnelles
Lorsque les gens d'affaires expriment des besoins, les TI mettent en place un projet pour livrer la solution. Cela peut prendre plusieurs formes :
- Développement sur mesure
- Achat d'un progiciel
- Utilisation d'un SaaS 
- Toute combinaison de ces éléments

Ces projets peuvent s'étaler sur des périodes allant de 3 à 24 mois ou plus, en fonction de la complexité, ce qui implique des coûts importants.

### L'émergence des DMU et le Shadow IT
Lorsque le besoin est circonscrit (par exemple, à une seule activité dans un processus), l'analyse bénéfices/coûts révèle bien souvent qu'il n'est pas rentable de développer une solution TI formelle. Le besoin, cependant, est bien réel et la frustration des équipes grandit.

Face à cette situation, les équipes d'affaires mettent en place leur propre DMU. Elles développent des solutions tactiques pour répondre à leurs besoins immédiats en utilisant les outils à leur disposition (Excel, scripting, etc.).

### Les « DMU sauvages » et les risques associés
Une véritable **culture de la DMU** finit par s'instaurer. Avec le temps, on observe l'apparition croissante de « DMU sauvages », développées sans aucun contrôle, qui exposent l'entreprise à divers risques TI (bris de sécurité, fuites de renseignements, non-conformité, etc.).

Malgré toutes les tentatives, souvent utopiques, de tout réguler ou de supprimer ces DMU, elles persistent et éclosent là où on s'y attend le moins. La chasse aux DMU devient un perpétuel jeu du chat et de la souris. Tant que les TI ne sauront pas livrer de manière agile *tous* les besoins d'affaires, aussi petits soient-ils, les DMU resteront la moins mauvaise des solutions pour continuer d'opérer les affaires.

### L'impact amplificateur de l'Intelligence Artificielle
L'avènement de l'IA (Intelligence Artificielle) vient amplifier ce phénomène. 

Quand il fallait avoir minimalement des compétences dans des outils (affaires) puissants (Excel, PowerBI, PowerAutomate, SAS, SQL, etc.) pour mettre en place des DMU, l'arrivée des assistants IA tel que Copilot Chat est pour les gens d'affaires une véritable aubaine pour augmenter les DMU de façon exponentielle. En effet, **c'est Copilot Chat qui va « coder » (ou assister le codage) de la DMU !**

### Le dilemme actuel : Coercition vs Optimisation
D'autres tentatives de coercition pour cadrer ces nouvelles pratiques, et donc proscrire la création de DMU, vont s'avérer vaines comme par le passé. La machine est en marche et on ne l'arrêtera pas, notamment pour les raisons suivantes :

1. **La pression pour l'optimisation** : L'entreprise veut optimiser et réduire les tâches manuelles (qui sont précisément le sujet principal des DMU !). Elle met la pression pour atteindre cet objectif d'une part, ce qui accélère l'adoption de l'IA (assistants IA tels que Copilot Chat, ChatGPT, etc.).
2. **Le contrôle du risque IA** : D'autre part, l'entreprise veut contrôler le risque IA en mettant des processus d'approbation supplémentaires pour la livraison des solutions impliquant l'IA (par exemple, fabriquer des chatbots spécialisés pour un métier afin de ne pas le faire de façon artisanale avec des assistants individuels). Cela prolonge un délai de livraison par les TI qui est déjà long.

On pousse donc la machine dans ses limites : le nombre de DMU créées avec des assistants IA va donc mécaniquement augmenter. 

### Le défi de l'IA responsable
En parallèle, pour faire bonne figure, l'entreprise tente de mettre en place des pratiques d'IA responsables (éthiques, écologiques, bien-être au travail, éviter la tendance des individus à tout déléguer aveuglément à l'assistant IA). 

Il devient de plus en plus difficile de concilier ces deux pôles : d'un côté, la volonté frénétique d'automatiser par les utilisateurs (facilitée par l'IA), et de l'autre, le besoin de gouvernance stricte et de pratiques responsables prônées par l'organisation.

## Une piste de solution : Accompagner plutôt que combattre

Plutôt que de se battre contre la machine et la nature humaine, la solution réside dans l'accompagnement de cette transformation. Il s'agit de **libérer le potentiel des individus "affaires"** à utiliser l'IA de manière responsable.

Comment y parvenir ?
- **Fournir des assistants IA de création de DMU professionnels** : Donner aux métiers les moyens de créer des DMU de qualité, encadrées par des outils adaptés (et approuvés), plutôt que de les laisser utiliser des solutions individuelles non contrôlées.
- **Démultiplier les capacités TI** : Permettre la création de ces DMU tactiques (qui représentent des capacités fonctionnelles) directement par les affaires. Ces DMU viables serviront ensuite de base pour intégrer plus facilement ces capacités aux solutions industrielles dont les TI ont la charge.

## Un exemple concret : Le processus d'octroi de prêts 

Imaginons une équipe qui opère un processus d'octroi de prêts dans une banque. Dans ce processus, une activité manuelle consiste à évaluer la valeur du bien convoité (objet du financement) afin d'établir une garantie "collatérale" en cas de défaut de remboursement.

> « Imaginez une équipe qui analyse une demande de financement de 75 000 $ CAD pour l'achat d'une excavatrice d'occasion. Avant de décaisser l'argent, l'équipe doit valider la juste valeur marchande de l'engin. L'objectif est de s'assurer que, si l'entreprise fait faillite, la banque peut reprendre l'équipement et le revendre rapidement à l'encan pour un montant proche de la dette restante. Cette étape permet de confirmer que la garantie (le bien lui-même) couvre bien le prêt. Si l'on réalise que l'équipement ne vaut en réalité que 50 000 $ CAD, la banque demandera probablement une mise de fonds plus importante pour réduire son risque. »

L'estimation de cette valeur marchande est effectuée par un des analystes de l'équipe, et ce, pour chaque demande (il peut y avoir plusieurs dizaines de milliers de demandes par an). Il constitue une estimation par analyse de comparables : il va sur internet et des sites spécialisés afin d'avoir plusieurs exemples de prix de vente ou de revente du bien et en déduit une estimation moyenne ou médiane.

Cette opération peut prendre, pour les plus aguerris, entre 15 et 20 minutes ! On pourrait tout à fait automatiser ceci.

Cependant, dans le contexte traditionnel :
- L'analyse coûts/bénéfices par les TI place souvent ce projet "d'optimisation de 15 minutes" en bas de la pile des priorités, face d'autres chantiers plus cruciaux pour la banque.
- Un DMU devient alors la seule opportunité viable pour aider cette équipe à atteindre son objectif d'automatisation de son processus (en partie certes, mais c'est déjà un début déterminant pour l'équipe) !

### Le mirage du prompt magique

Une solution avec un assistant IA (comme Copilot Chat par exemple) est alors mise en place par les affaires. Un "prompt" et le tour est joué !

**Oui, mais non.**

L'expérience prouve que ce n'est pas si simple. Plusieurs facteurs échappent au contrôle de l'utilisateur et influencent grandement le résultat de l'estimation :
- **La qualité du prompt** : Elle varie fortement d'un utilisateur à l'autre.
- **La version du modèle (LLM)** : Le modèle appelé sous le capot peut changer sans préavis.
- **La capacité et le routage des serveurs** : Selon la charge, la requête peut être routée (à l'insu de l'utilisateur) vers un modèle moins performant ou plus rapide, altérant la précision.
- **La personnalisation de l'environnement** : L'environnement de chat de chaque analyste possède ses propres réglages et son propre historique, ce qui biaise l'uniformité des réponses.
- **Le comportement d'hallucination / de lecture réseau** : La capacité de l'assistant à aller lire les *bons* sites est incertaine. L'IA peut prétendre avoir consulté un lien précis alors qu'en réalité elle a inventé ou agrégé d'autres informations (comme cela a déjà été démontré dans de nombreux cas).

### Le risque métier avéré

Nous sommes ici face à un cas d'école : une **DMU assistée par l'IA qui semble bien fonctionner en apparence**, mais qui présente de multiples risques sournois.

Surtout, cette pratique contrevient souvent aux politiques internes de l'entreprise : le résultat d'une IA non contrôlée est ici pris en compte dans une décision d'affaires financière critique. 

Même si le processus stipule que l'analyste *doit vérifier* ce que produit l'IA, la réalité du terrain rattrape la théorie :
- Le fait-il réellement à chaque fois ?
- S'il doit passer 15 minutes à contre-vérifier méticuleusement toutes les sources de l'IA pour s'assurer qu'elle n'a pas halluciné un prix... quel est alors le gain de temps initial ? 

L'automatisation perd tout son sens si le temps de vérification égale le temps d'exécution manuelle.

### Mitiger les risques : L'illusion du "bon prompt"

Certains de ces risques peuvent, en théorie, être mitigés sans changer d'approche : 
On peut écrire un prompt testé et "certifié", puis le partager avec toute l'équipe. On peut aussi demander à l'utilisateur de désactiver ses personnalisations avant d'exécuter le prompt. 

Mais dans la pratique :
- Le prompt sera-t-il utilisé tel quel, sans aucune modification ? (Aucun contrôle possible).
- L'analyste n'oubliera-t-il pas de désactiver ses réglages ?
- Le fera-t-il s'il n'en comprend pas la véritable utilité technique ?

Bref, on peut toujours tenter de "coller des rustines" sur cette DMU, mais la fondation reste fragile et incontrôlable.

### La véritable solution : L'Agent Métier créé par un Expert en Automatisation

Si nous avions placé au sein de cette direction (ou de cette entité) un **expert IA** (ou plus justement un *expert en automatisation de processus par l'IA*), proche du terrain et de l'équipe, la dynamique aurait été totalement différente.

Muni d'un outil professionnel tel que Copilot Studio (fourni et sécurisé par les TI en tant qu'"outil de fondation" pour des DMU sécuritaires), cet expert aurait pu paramétrer et mettre à disposition un **Agent Métier** spécifique pour ce besoin.

Avec cette approche professionnelle, l'expert peut :
- **Cadrer le prompt** de manière invisible et immuable pour l'utilisateur.
- **Restreindre les sources** de connaissances aux seuls sites autorisés et fiables.
- **Forcer l'utilisation d'un modèle** spécifique et constant.
- **Ajouter un workflow de vérification** avec des sous-agents vérificateurs avant d'afficher le résultat.
- **Obtenir de vraies métriques d'utilisation** et des journaux d'exécution (logs) pour permettre une surveillance et un audit (choses impossibles avec l'approche "prompt partagé").

En somme, on règle ainsi la grande majorité des risques, tout en fournissant une solution performante aux affaires !

### Passer à l'échelle : Une question de volonté politique

La clé réside donc dans le fait de disposer de ces experts en automatisation dans les différentes directions d'affaires, et de généraliser cette approche aux milliers d'activités manuelles qui font aujourd'hui l'objet de DMU sauvages.

Il faut :
1. Les positionner au plus près des besoins d'affaires.
2. Les former correctement.
3. Leur donner les bons outils de fondations (approuvés et mis à disposition par les TI).

Cette synergie entre les TI (qui fournissent le cadre et les outils sécuritaires) et les affaires (qui développent leurs "Agents DMU" de façon contrôlée) est réalisable. **C'est avant tout une question de volonté politique et de changement de paradigme organisationnel.**

## La touche finale : L'écologie et l'architecture

Si l'on pousse la réflexion encore plus loin : a-t-on *vraiment* besoin d'une IA pour faire cette tâche d'estimation ? 

Si les TI avaient développé une solution industrielle pour ce besoin précis, auraient-ils mis en place un chatbot ? **La réponse est non !** 
*Quand le seul outil que l'on possède est un marteau, toutes les solutions ont la forme d'un clou.* 

Une solution TI classique et optimisée consisterait à récupérer les valeurs via des API (ou à défaut par du Web Scraping), effectuer les calculs de manière déterministe, et produire un rapport sur une page Web ou un document prêt à être collé dans le dossier de l'analyste.

### L'Assistant de Codage : La capacité TI décentralisée
C'est ici qu'intervient une approche encore plus fantastique. Si l'on donne à ces experts en automatisation la capacité d'utiliser un **assistant de codage (Agent de développement)** spécifiquement ciblé pour produire des DMU de qualité, on offre littéralement la capacité TI manquante aux gens d'affaires !

Cet assistant de codage prend le besoin d'affaires et *code* une véritable solution (script, petite application web) qui peut tourner localement dans un espace utilisateur sécurisé. 

Bien sûr, il faut former ces experts pour qu'ils sachent collaborer avec des agents de codage (on parle ici d'**agentique** ou de **vibe coding**). Il ne s'agit pas simplement de dicter une commande, mais de savoir assumer le rôle de *Product Owner (PO) Technique* au sein d'une équipe virtuelle composée de plusieurs rôles IA (architecture, développement, test).

### La boucle est bouclée : L'impact écologique (Les Tokens)
Le lien avec l'écologie est direct et frappant.

Avec une solution de type "Copilot Chat" ou "Copilot Studio" (l'approche marteau), l'entreprise dépense une quantité astronomique de *tokens* en inférence **à chaque estimation**. Multipliez cela par le nombre de tentatives par dossier, par les dizaines de milliers de dossiers annuels, et par l'ensemble des DMU "faussement IA" de l'entreprise : le coût énergétique et financier est colossal.

À l'inverse, si l'on utilise un assistant de codage basé sur l'IA (qui consomme certes beaucoup de tokens *pendant* la phase de réalisation de la solution), le résultat final est une application classique (non-IA). 
**En phase d'utilisation (run) : la consommation de tokens est de 0.**

La boucle est ainsi parfaitement bouclée : on optimise les processus d'affaires (DMU), grâce à l'IA, tout en respectant un principe fondamental d'IA responsable et écologique !

---

## Objectif du Projet

Ce dépôt (workspace DMU) a pour but de **mettre en place un cadre de développement agentique pour des DMU responsables et efficaces**. 

Nos travaux se concentreront sur :
1. **La définition des "skills" (compétences)** nécessaires aux agents IA pour assister les experts en automatisation dans la création de DMU.
2. **La formalisation des spécificités** de ces DMU de nouvelle génération (les "Agents DMU").
3. **Le test et la validation** sur différents cas pratiques génériques (seuls des cas transposables à d'autres contextes d'affaires seront exposés ici, afin d'en démontrer la valeur universelle).
