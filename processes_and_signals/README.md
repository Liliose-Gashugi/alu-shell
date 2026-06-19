# Processes and Signals

Bash scripting project covering process management, signal handling, and PID files.

## Environment
- Interpreted on **Ubuntu 20.04 LTS**
- All scripts begin with `#!/usr/bin/env bash`
- All scripts pass **Shellcheck (v0.7.0)** without errors

## Files

| File | Description |
|---|---|
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Lists all running processes in user-oriented format with hierarchy |
| `2-show_your_bash_pid` | Filters processes for those containing "bash" |
| `3-show_your_bash_pid_made_easy` | Same as above without using `ps` |
| `4-to_infinity_and_beyond` | Prints "To infinity and beyond" indefinitely |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` using `kill` |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` without `kill` or `killall` |
| `7-highlander` | Infinite loop that responds to SIGTERM with "I am invincible!!!" |
| `67-stop_me_if_you_can` | Stops `7-highlander` (sends SIGTERM, gets trapped) |
| `8-beheaded_process` | Kills `7-highlander` with SIGKILL (untrappable) |
| `10-process_and_pid_file` | Creates a PID file, handles SIGINT/SIGTERM/SIGQUIT |
| `manage_my_process` | Background daemon that writes "I am alive!" to a file |
| `11-manage_my_process` | Init script to start/stop/restart `manage_my_process` |

## Author
Liliose Gashugi Muhimpundu
