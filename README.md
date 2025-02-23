# GitDemo Repo

this is a sample repository / sample app for the git course

## How To Work With Git

| Step | Git | Command    | Switch | Branch             |
| ---- | --- | ---------- | ------ | ------------------ |
| 1    | git | `checkout` |        | main               |
| 2    | git | `pull`     |        |                    |
| 3    | git | `checkout` | -b     | bug-##-branch-name |
| 4    | git | `add`      | .      |                    |
| 5    | git | `commit`   |        |                    |
| 6    | git | `checkout` |        | main               |
| 7    | git | `pull`     |        |                    |
| 8    | git | `checkout` |        | bug-##-branch-name |
| 9    | git | `merge`    |        | main               |
| 10   | git | `checkout` |        | main               |
| 11   | git | `merge`    |        | bug-##-branch-name |
| 12   | git | `pull`     |        |                    |
| 13   | git | `push`     |        |                    |
| 14   | git | `branch`   | -d     | bug-##-branch-name |

</br>

## Other Useful commands

| Git | Command                    | Description                         |
| --- | -------------------------- | ----------------------------------- |
| git | `remote`                   | Lists remotes connected to repo     |
| git | `remote show orign`        | Shows branches on remote            |
| git | `push -u origin` branch    | Pushes branch to the remote         |
| git | `reset --hard origin/main` | Reset current branch to remote head |
| git | `revert` GUID              | Revert commit by id                 |
| git | `amend`                    | Amend last commit or message        |

## Road Map

- Add new features
- Fix the bugs

## Coming next - Pull Requests
