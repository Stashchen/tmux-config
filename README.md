# tmux configuration

Here is my tmux configuration
[Tmux plugin manager]("https://github.com/tmux-plugins/tpm") must be installed

## How to set configuration file?
All you need to do is to move `.tmux.conf` file to your user home page (`/home/<user>/`)

## Useful tmux shortcuts
**NOTE:** current prefix for tmux commands is `Ctrl + a`

### Session
- Create session with name
```bash
# In terminal
$ tmux new -s <session-name>
```
- Get list of valid sessions:
```bash
# In terminal
$ tmux ls
```
- Connect to valid session:
```bash
$ tmux attach  # Will connect to the latest/single one
$ tmux attach -t <session_name>
```
- Kill all sessions:
```bash
$ tmux kill-server
```
- Detach from session: `<prefix> + d`
### Windows 
- Create new window: `<prefix> + c` 
- Create new window with name: `<prefix> + C`
- Get the list of valid windows: `<prefix> + w`  
- Close current window: `<prefix> + x`
### Movement
- Go to next window: `<prefix> + n`
- Go to previous window: `<prefix> + p`
- Go to window by number: <prefix> + <window_num>`
### Splitting
- Split window horizontally: `<prefix> + "`
- Split window verticaly: `<prefix> + [%|v]`

