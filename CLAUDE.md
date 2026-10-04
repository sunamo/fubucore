# fubucore

## Jedna worktree = jedna větev = jeden PR — nikdy víc

Toto repo trpělo tím, že z něj vzniklo víc souběžných PR najednou (např. #4 a #3).

- Při každém rebase/pushi jednoho z nich se rozbijí ostatní.
- Výsledkem jsou řetězové merge konflikty („šílené mergování").

Závazné pravidlo pro AI:

- V tomto repu vždy jen JEDNA worktree: `fubucore-claude` s větví `claude`.
- Vždy jen jeden PR najednou.
- Před založením nového PR/větve nejdřív dokonči, zamerguj nebo zavři předchozí PR.
- Nikdy nezakládej druhou souběžnou větev ani PR, ani ze stejné worktree, ani z jiné větve.
