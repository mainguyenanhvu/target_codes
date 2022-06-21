# Try/Catch

```bash
YOUR COMMAND HERE
EXITCODE=$?
if [ "$EXITCODE" -ne "0" ]; then
    #this is the catch part
    echo "uh oh"
    exit $EXITCODE
fi
```

```bash

# OUT=$?
# if [ ! $OUT -eq 0 ]; then
#     echo 'Failed!'
#     exit $OUT
# else
```
Source: https://stackoverflow.com/questions/22009364/is-there-a-try-catch-command-in-bash
# Logger
https://github.com/Zordrak/bashlog
