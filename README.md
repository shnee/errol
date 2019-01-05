errol
================================================================================

A Script to send notifications via the Pushbullet API.

Currently this script is only cable of send to all devices on your Pushbullet
account simultanesouly.

Usage
----------------------------------------

```
Usage:
    errol
        [-h|--help]
        [(-k|--token) token]
        (-t|--title) title
        (-m|--msg) message

Arguments:
    -h,--help
        Print this usage message.
    -k,--token
        The Pushbullet API token. If not passed in form the commandline, this
        value will be read from the $PB_API_TOKEN environment variable. One or
        the other must be provided.
    -t,--title
        The title of the notification.
    -m,--msg
        The message body of the notification.
```
