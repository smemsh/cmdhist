cmdhist
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

TODO PLACEHOLDER REPO

For now this is so tied to https://github.com/smemsh/taskwtools/
that it's being tracked in that repository (in the ``cmdhist``
script therein).

Eventually we'll modularize it and decouple, split the history
and bring it over here.  It doesn't necessarily need to have the
task FQL in the cmdhist; still generically useful without that
(it just makes more sense to join it with timewarrior history if
you're using taskwtools).

The script also needs the ``init.d/history`` component from
https://github.com/smemsh/.bashrc to insert into the sqlite3
database in $PROMPT_COMMAND, and there are a bunch of hardcoded
paths, etc and that needs to be decouped as well.

So very specific to my stuff at the moment.

Therefore, this repo is only a placeholder at the moment.
