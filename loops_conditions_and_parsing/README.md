# Loops, Conditions and Parsing

Bash scripting project covering loops (`for`, `while`, `until`), conditionals (`if`, `case`), and parsing of system files and Apache logs.

## Environment
- Interpreted on **Ubuntu 20.04 LTS**
- All scripts begin with `#!/usr/bin/env bash`
- All scripts pass **Shellcheck (v0.7.0)** without errors

## Files

| File | Description |
|---|---|
| `1-for_best_school` | Displays "Best School" 10 times using `for` |
| `2-while_best_school` | Displays "Best School" 10 times using `while` |
| `3-until_best_school` | Displays "Best School" 10 times using `until` |
| `4-if_9_say_hi` | Displays "Best School" 10 times, with "Hi" after the 9th iteration |
| `5-4_bad_luck_8_is_your_chance` | Loops 1–10 with `if/elif/else` for luck messages |
| `6-superstitious_numbers` | Displays 1–20 with superstitious notes using `case` |
| `7-clock` | Displays hours 0–12 and minutes 1–59 |
| `8-for_ls` | Lists current directory entries, showing only text after the first dash |
| `9-to_file_or_not_to_file` | Inspects the `school` file using `if/else` |
| `10-fizzbuzz` | Classic FizzBuzz from 1 to 100 |
| `11-read_and_cut` | Displays username, UID, and home directory from `/etc/passwd` |
| `12-tell_the_story_of_passwd` | Narrative version of `/etc/passwd` using `while` + `IFS` |
| `13-lets_parse_apache_logs` | Extracts IP and HTTP status code from Apache logs |
| `14-dig_the-data` | Groups Apache log entries by IP + status, sorted by frequency |

## Author
Liliose Gashugi Muhimpundu
