Workflows in this directory are used to configure Integra.

Add-Providers: adds all Java-based providers on the default ports, running on localhost.

_Purge-Integra: removes all schedule results, schedules, workflows, actions, and providers.  EXCEPT those whose name starts with an underscore.  This workflow contains individual actions to delete each component.

_Nuke: does the same thing as _Purge-Integra, except it does it in one big script.


