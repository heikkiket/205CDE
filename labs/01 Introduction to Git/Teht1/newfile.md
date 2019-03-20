Koska olin tehnyt ensimmäiset tehtävät erilliseen Git-repositoryyn, jouduin opettelemaan subtree-yhdistämisen.
Kaksi git-repoa voi yhdistää subtree-toiminnon kautta. Yhdistäminen säilyttää historian:

    $ git subtree add --prefix=01-git-testailua git@github.com:heikkiket/git-testailua.git master

Neuvoin saman myös luokkakaverilleni Suville. Repon historiasta näkee, että tällainen subtree-merge tuli tehtyä.