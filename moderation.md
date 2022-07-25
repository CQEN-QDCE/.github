<!-- ENTETE -->
[![img](https://img.shields.io/badge/Lifecycle-Experimental-339999)](https://www.quebec.ca/gouv/politiques-orientations/vitrine-numeriqc/accompagnement-des-organismes-publics/demarche-conception-services-numeriques)
[![License](https://img.shields.io/badge/Licence-LiLiQ--R-blue)](LICENSE_FR)

---

<div>
    <img src="../images/mcn.png">
</div>
<!-- FIN ENTETE -->

# Politique de modération

Ce document décrit comment la modération se produit dans le collectif.
Il décrit comment les gens peuvent gérer les violations du code de conduite.
De plus, il décrit les actions de tout responsable, et plus particulièrement des modérateurs
(responsables de l'équipe de modération collective).

Ce document est élaboré par l'équipe de modération collective unifiée et le
noyau collectif unifié.

## Table des matières

* [Violations](#violations)
     * [Rapport](#rapport)
     * [Application](#application)
* [Playbooks](#playbooks)
     * [Modération](#modération)
     * [Avertissement](#avertissement)
     * [Expulsion](#expulsion)
     * [Blocage](#blocage)

## Violations

Une **violation**, dans le cadre de la gouvernance collective, est toute publication qui
viole le [code de conduite][coc].
L'équipe de modération collective décide quel comportement inapproprié constitue un
violation.

Une publication inclut une activité qui peut être modérée, telle que du code, des commentaires, des commits,
des modifications, des `issues`, des publications ou des `pull requests`, dans un projet régi par le collectif.
Les messages incluent en outre des activités qui ne peuvent pas être modérées, telles que des e-mails ou
tweets, de membres du collectif.

La **modération**, dans le cadre de la gouvernance collective, comprend des actions telles que
modifier, supprimer, masquer ou verrouiller un ou plusieurs messages pour remédier aux violations.
Tous les messages ne peuvent pas être modérés.

Ces actions ne sont pas considérées comme de la modération si elles ne traitent pas des violations,
telles que des modifications mineures pour corriger le formatage ou les fautes de frappe, masquer les messages obsolètes ou
verrouiller les anciens `issues`.

Les personnes doivent examiner attentivement l'intention possible de l'auteur d'une
violation.
Il se peut qu'ils aient fait une erreur, qu'ils ne connaissent pas le code de conduite,
ignorent que quelque chose est inapproprié ou qu'il existe des différences culturelles.
Dans de tels cas, l'auteur peut avoir la possibilité de corriger l'erreur qu'il a
fabriqué.
Cela n'excuse pas une violation, mais il vaut parfois mieux informer un auteur
que l'exécution.

Les violations doivent être signalées et peuvent entraîner des sanctions telles que la modération,
avertissement, blocage et expulsion.

Cette politique n'empêche aucune personne de bloquer une autre personne de
leur compte GitHub personnel (ou dans un autre espace, comme Twitter).
Un blocage personnel n'est pas considéré comme une application de la modération.

### Rapports

N'importe qui peut signaler une infraction.
Les membres doivent signaler les violations.
Les violations peuvent être signalées des manières suivantes :

* En privé, via l'adresse mail collective `moderation@ministere.gouv.qc.ca`
* En privé, par email à un ou plusieurs modérateurs
* En public, via un nouveau post dans le même fil de discussion que la violation (mentionnant
    `@projet/modérateurs`)

Le signalement en privé est approprié lorsque le rapporteur ne se sent pas à l'aise
directement ou publiquement la demande.
Les rapports envoyés à `moderation@ministere.gouv.qc.ca` sont transmis à tous les mainteneurs de
l'équipe de modération collective.

Les rapports doivent contenir autant d'informations et de contexte que possible, y compris
l'URL et une capture d'écran de la violation.
Les détails peuvent être modifiés pour masquer le contenu obscène ou offensant.
Le fait de citer le contenu original d'une violation dans un rapport n'est pas une violation.
Cependant, la discrétion est recommandée lors de l'inclusion de telles citations dans des rapports publics.

Les membres ne doivent pas discuter des détails spécifiques des rapports dans un espace public.

Les violations sont signalées pour suivre les violations, leur contexte et les conséquences qui en résultent.
l'application, à travers le collectif.

Les rapports sont également utilisés pour suivre les violations dans le collectif.

### Mise en vigueur

Les modérateurs peuvent appliquer la modération, l'avertissement, l'expulsion et le blocage.

Si la violation provient d'un utilisateur (un individu qui n'est pas membre), tout
mainteneur peut appliquer la modération et le blocage.

Les modérateurs peuvent **modérer** n'importe quel message, et les responsables peuvent modérer un message d'un
utilisateur, en suivant (si possible) le `playbook` de *modération*.

Pour les violations extrêmes, les modérateurs peuvent **expulser** n'importe quel membre en suivant le `playbook`
*expulsion*, et ils peuvent aussi **bloquer** toute personne; les mainteneurs peuvent bloquer un utilisateur, 
en suivant le `playbook` de *blocage*.

Les modérateurs doivent garder une trace des violations (qui sont en effet des délits) de
un délinquant.

Les première et deuxième infractions doivent entraîner le `playbook` d'*avertissement*.
Une troisième infraction, si le contrevenant est membre, doit entraîner le `playbook` d'*expulsion*.
Une troisième infraction (ou la quatrième infraction, si le contrevenant est expulsé) doit entraîner
le `playbook` de *blocage*.

## Playbooks

Les `playbooks` décrivent les étapes qu'un acteur doit suivre pour mettre en œuvre l'application du
code de conduite.

### Modération

L'acteur d'un `playbook` de *modération* est un mainteneur.

Le contrevenant est une personne qui a commis une infraction.

Le résultat de la *modération* est qu'une violation n'est plus présente.

* L'acteur s'assure que la violation est signalée
* Si le contrevenant est un membre, l'acteur doit donner au contrevenant une
     possibilité raisonnable d'auto-modérer le message.
     Si le délinquant n'est pas d'accord avec l'auto-modération, l'acteur peut passer à la
     équipe de modération collective, en assurant le suivi du signalement, sans
     continuer à faire preuve de modération.
     Les modérateurs peuvent décider de continuer à adopter la modération.
* L'acteur modère la publication, par exemple en modifiant, supprimant, masquant ou verrouillant.
* L'acteur publie une notification dans le fil de discussion d'origine, mentionnant le
     contrevenant, qu'il enfreint le code de conduite, quel comportement
     était inacceptable, quels changements ont été apportés au poste et pris les
     étapes précedentes pour résoudre, au bout de justifier pourquoi la modération était faite.

### Avertissement

L'acteur d'un `playbook` *avertissement* est un modérateur (un mainteneur de
l'équipe de modération collective).
Le contrevenant est une personne qui a commis une infraction pour la première ou la deuxième fois.
Le résultat d'un *avertissement* est qu'un délinquant est conscient que son comportement est
en violation du code de conduite, que le code de conduite est appliqué, 
et des futures mesures d'exécution pour les violations peuvent être appliquées.

* L'acteur publie un avertissement dans le fil d'origine, confirmant le
     justification de la modération, que c'était leur première ou 
     deuxième avertissement officiel et comment une troisième violation sera appliquée. 

### Expulsion

L'acteur d'un `playbook` d'*expulsion* est un modérateur (un mainteneur de
l'équipe de modération collective).
Le contrevenant est un membre qui a commis une violation extrême ou en continu.
Le `playbook` *expulsion* est suivi après modération (rapide).
Le résultat de l'*expulsion* est qu'un membre est dispensé de ses fonctions et démis de ses fonctions 
dans toutes les équipes.

* L'acteur s'assure que la violation est signalée
* L'acteur se coordonne avec un mainteneur de l'équipe de base collective pour
    et promulguez rapidement le `playbook` d'*offboarding* pour toutes les équipes d'ou le contrevenant
    est actuellement membre, mais au lieu d'attribuer un nouveau rôle, les supprimer
    entièrement
* L'acteur poste message dans le fil de discussion d'origine, mentionnant l'auteur de l'infraction,
    expliquant quel comportement était inacceptable, qu'il s'agissait de la
    troisième violation ou une violation extrême, et confirmant qu'il est 
    expulsé du collectif

L'expulsion représente un risque imminent pour le collectif car elle pourrait pousser le
délinquant d'agir d'une extrême mauvaise foi et d'abuser des autorisations qui lui étaient accordées. 

### Blocage

L'acteur d'un `playbook` *blocage* est un modérateur (un mainteneur de
l'équipe de modération collective) et dans certains cas un mainteneur.
Le contrevenant est une personne qui a commis une violation extrême ou une
troisième (ou quatrième) infraction.
Le résultat du *blocage* est qu'un délinquant est expulsé de force 
des espaces régis par le collectif.

* L'acteur s'assure que la violation est signalée
* L'acteur se coordonne avec un mainteneur de l'équipe de base collective pour
    bloquer le contrevenant dans les espaces régis par le collectif, comme GitHub
    et Twitter
* Messages de l'acteur dans le fil de discussion d'origine, mentionnant l'auteur de l'infraction,
    expliquant quel comportement était inacceptable, qu'il s'agissait de la
    troisième/quatrième violation ou une violation extrême, et confirmant qu'il est
    bloqué du collectif

GitHub fournit une interface pour bloquer des personnes pendant 1, 3, 7 ou 30 jours, ou
indéfiniment.
Cette politique ne dicte pas intentionnellement si le blocage est temporaire ou
indéfinie, et laisse cela aux modérateurs.

<!-- Definitions -->

[coc]: ./CODE_OF_CONDUCT.md


--- 

(Exemple tiré et adapté de https://github.com/unifiedjs/collective/blob/HEAD/moderation.md).