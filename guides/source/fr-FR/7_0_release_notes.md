**NE LISEZ PAS CE FICHIER SUR GITHUB, LES GUIDES SONT PUBLIÉS SUR https://guides.rubyonrails.org.**

Notes de Mise à Jour de Ruby on Rails 7.0
=========================================

Résumé de Rails 7.0:

* Ruby 2.7.0+ requis, Ruby 3.0+ préferé

--------------------------------------------------------------------------------

Mettre à Niveau vers Rails 7.0
------------------------------

Si vous mettez à niveau une application existante, c'est une bonne idée d'avoir une bonne couverture de votre code par des tests avant de vous lancer. Vous devriez également effectuer une mise à niveau vers Rails 6.1 au cas où vous ne l'auriez pas encore faite et vous assurer que votre application fonctionne toujours comme prévu avant d'essayer une mise à niveau vers Rails 7.0. Une liste de choses à surveiller lors de la mise à niveau est disponible dans le guide de
[Mise à Niveau Ruby on Rails](upgrading_ruby_on_rails.html#upgrading-from-rails-6-1-to-rails-7-0).

Principales fonctionnalités
---------------------------

Railties
--------

Veuillez vous référer au [Changelog][railties] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action Cable
------------

Veuillez vous référer au [Changelog][action-cable] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action Pack
-----------

Veuillez vous référer au [Changelog][action-pack] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action View
-----------

Veuillez vous référer au [Changelog][action-view] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action Mailer
-------------

Veuillez vous référer au [Changelog][action-mailer] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Active Record
-------------

Veuillez vous référer au [Changelog][active-record] pour le détail des changements.

### Suppressions

*   Supprimer le kwarg obsolète `database` de `connected_to`.

### Dépréciations

### Changements notables

Active Storage
--------------

Veuillez vous référer au [Changelog][active-storage] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Active Model
------------

Veuillez vous référer au [Changelog][active-model] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Active Support
--------------

Veuillez vous référer au [Changelog][active-support] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Active Job
----------

Veuillez vous référer au [Changelog][active-job] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action Text
----------

Veuillez vous référer au [Changelog][action-text] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Action Mailbox
----------

Veuillez vous référer au [Changelog][action-mailbox] pour le détail des changements.

### Suppressions

### Dépréciations

### Changements notables

Ruby on Rails Guides
--------------------

Veuillez vous référer au [Changelog][guides] pour le détail des changements.

### Changements notables

Crédits
-------

Consultez la [liste complète des contributeurs Rails](https://contributors.rubyonrails.org/) qui conteient les noms des nombreuses personnes qui ont passé de nombreuses heures à faire de Rails le framework stable et robuste qu'il est aujourd'hui. Félicitations à tous.

[railties]:       https://github.com/rails/rails/blob/main/railties/CHANGELOG.md
[action-pack]:    https://github.com/rails/rails/blob/main/actionpack/CHANGELOG.md
[action-view]:    https://github.com/rails/rails/blob/main/actionview/CHANGELOG.md
[action-mailer]:  https://github.com/rails/rails/blob/main/actionmailer/CHANGELOG.md
[action-cable]:   https://github.com/rails/rails/blob/main/actioncable/CHANGELOG.md
[active-record]:  https://github.com/rails/rails/blob/main/activerecord/CHANGELOG.md
[active-storage]: https://github.com/rails/rails/blob/main/activestorage/CHANGELOG.md
[active-model]:   https://github.com/rails/rails/blob/main/activemodel/CHANGELOG.md
[active-support]: https://github.com/rails/rails/blob/main/activesupport/CHANGELOG.md
[active-job]:     https://github.com/rails/rails/blob/main/activejob/CHANGELOG.md
[action-text]:    https://github.com/rails/rails/blob/main/actiontext/CHANGELOG.md
[action-mailbox]: https://github.com/rails/rails/blob/main/actionmailbox/CHANGELOG.md
[guides]:         https://github.com/rails/rails/blob/main/guides/CHANGELOG.md
