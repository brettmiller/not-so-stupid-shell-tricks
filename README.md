# Not so stupid shell tricks

### Slides and videos from a lighting talk on shell tricks

Below are all the keystrokes/commands in the presentation for quick reference

<br>

## Start with a clean slate

|Keystroke          | Description
---                 |---
| CTRL-l            | clear the screen without using the `clear` command

## Histroy

|Keystroke/command  | Description
---                 |---
| CTRL-p / CTRL-n   | Go back in history list/go forward in history list
| CTRL-r            | Reverse search history.
| ^foo^bar          | Replace ‘foo’ with ‘bar’ in first matching string of previous command
| !!:gs/foo/bar/    | Replace ’foo’ with ‘bar’ globally (for all matches of ‘foo’) in previous command  (!!:s/foo/bar/ is the same as ^foo^bar) 
| !!                | Refer to previous command (in full)
| ESC . / ALT-.     | Insert last argument to previous command (tap ESC then .)

## Movement

| Keystrokes             | Descritption
---                      |---
| CTRL-a / CTRL-e        | go to beginning/end of line|
| CTRL-f / CTRL-b        | move forward/backward one character|
| ALT-f / ALT-b          | move forward/backwards one word|
| CTRL-d / CTRL-h        | delete forward/backward from cursor one character|
| ALT-d / ALT-backspace  | delete forward/backward from cursor one word|
| CTRL-w                 | alternate of ALT-backspace|
