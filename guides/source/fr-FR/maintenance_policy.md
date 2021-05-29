**NE LISEZ PAS CE FICHIER SUR GITHUB, LES GUIDES SONT PUBLIÉS SUR https://guides.rubyonrails.org.**

Politique de Maintenance pour Ruby on Rails
===========================================

Le support du framework Rails est divisé en quatre groupes: Nouvelles fonctionnalités, corrections de bugs, problèmes de sécurité et problèmes de sécurité graves. Ils sont traités comme suit, pour toutes les versions, à l'exception des versions de sécurité, au format «X.Y.Z».

--------------------------------------------------------------------------------

Rails suit une version modifiée de [semver](https://semver.org/):

**Correction `Z`**

Seulement des corrections de bogues, pas de changements d'API, pas de nouvelles fonctionnalités.
Sauf si nécessaire pour les correctifs de sécurité.

**Mineure `Y`**

Nouvelles fonctionnalités, peut contenir des modifications de l'API (Servir comme les versions majeures de Semver).
Les changements entraînant des modifications du code sont associées à des notices d'obsolescence dans la version mineure ou majeure précédente.

**Majeure `X`**

Nouvelles fonctionnalités, contiendra probablement des modifications de l'API. La différence entre les versions mineures et majeures de Rails est l’ampleur des changements entraînant des modifications du code, et les versions majeures sont habituellement réservées aux occasions spéciales.

Nouvelles Fonctionnalités
-------------------------

Les nouvelles fonctionnalités ne sont ajoutées qu'à la branche principale et ne seront pas disponibles dans les versions ponctuelles.

Corrections de bogues 
---------------------

Seule la dernière série de versions recevra des corrections de bogues. Quand suffisamment de bogues sont corrigés et il est jugé utile de publier une nouvelle gem, c'est la branche depuis laquelle cela arrivera.

Dans des situations spéciales, où un membre de la Core Team accepte de soutenir le maintien de plus de séries de versions, elles sont inclues dans la liste des séries prises en charge.

**Séries actuellement incluses:** `7.0.Z`.

Problèmes de Sécurité
---------------------

La série de versions actuelle et la prochaine plus récente recevront des correctifs
et de nouvelles versions en cas de problème de sécurité.

Ces versions sont créées en prenant la dernière version publiée, en appliquant les
correctifs de sécurité et en les publiant. Ces correctifs sont ensuite appliqués à la fin de la branche x-y-stable. Par exemple, une version de sécurité 1.2.2.1 théorique
serait contruite à partir de la version 1.2.2, puis ajouté à la fin de la version 1-2-stable. Cela signifie qu'il est facile de mettre à niveau des dernières versions de sécurité si vous exécutez la dernière version de Rails.

Seuls les correctifs de sécurité directs seront inclus dans les versions de sécurité. Les corrections pour les bogues non liés à la sécurité résultant d'un correctif de sécurité peuvent être publiés sur une branche x-y-stable de la version, et ne sera publiée qu'en tant que nouvelle gem conformément à la politique de correction de bogues.

**Séries actuellement incluses:** `7.0.Z`, `6.1.Z`, `5.2.Z`.

Problèmes de Sécurité Graves
----------------------------

Pour les problèmes de sécurité graves, toutes les versions de la série majeure actuelle, ainsi que la dernière version de la série majeure précédente recevront des correctifs et de nouvelles versions. La classification du problème de sécurité est déterminée par la Core Team.

**Séries actuellement incluses:** `7.0.Z`, `6.1.Z`, `6.0.Z`, `5.2.Z`.

Séries de Versions Non Prises en Charge
---------------------------------------

Lorsqu'une série de versions n'est plus prise en charge, il relève de votre responsabilité de gérer les bogues et les problèmes de sécurité. Nous pouvons fournir des rétroportages des correctifs et les publier sur git, mais aucune nouvelle version ne sera publiée. Si vous n'êtes pas à l'aise avec la maintenance de vos propres versions, vous devriez passer à une version prise en charge.
