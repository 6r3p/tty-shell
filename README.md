# TTY Shell

Commonly used upgrades to a TTY shell for easy grabbing.

## Python

```shell
python -c 'import pty; pty.spawn("/bin/bash")'
```

## Python3

```shell
python3 -c 'import pty; pty.spawn("/bin/bash")'
```

## Bash

```shell
/bin/bash -i
```

## Echo

```shell
echo 'os.system('/bin/bash')'
```
