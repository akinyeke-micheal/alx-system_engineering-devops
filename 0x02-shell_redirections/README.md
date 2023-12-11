0x02-shell_redirections
This directory contains a series of scripts designed to handle standard input and output, and to combine commands and filters with redirections in Shell. The scripts are designed to be used during Full Stack Software Engineering studies at Holberton School.

Directory Structure
The scripts are named numerically, with each script serving a specific purpose:

.
├── 0-hello_world
├── 101-gifs
├── 102-acrostic
├── 103-the_biggest_fan
├── 3-twofiles
├── 7-file
├── 8-cwd_state
├── 9-duplicate_last_line
├── 10-no_more_js
├── 11-directories
├── 12-newest_files
├── 13-unique
├── 14-findthatword
├── 15-countthatword
├── 16-whatsnext
├── 17-hidethisword
├── 18-letteronly
└── 19-AZ
Script Descriptions
0-hello_world: Prints "Hello, World", followed by a new line to the standard output.
101-gifs: Lists all the files with a .gif extension in the current directory and all its sub-directories.
102-acrostic: Decodes acrostics that use the first letter of each line.
103-the_biggest_fan: Parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
3-twofiles: Displays the content of /etc/passwd and /etc/hosts.
7-file: Creates a file named exactly \'"Best School"'\$?*****:) containing the text Best School ending by a new line.
8-cwd_state: Writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9-duplicate_last_line: Duplicates the last line of the file iacta.
10-no_more_js: Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11-directories: Counts the number of directories and sub-directories in the current directory.
12-newest_files: Displays the 10 newest files in the current directory.
13-unique: Takes a list of words as input and prints only words that appear exactly once.
14-findthatword: Displays lines containing the pattern “root” from the file /etc/passwd.
15-countthatword: Displays the number of lines that contain the pattern “bin” in the file /etc/passwd.
16-whatsnext: Displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17-hidethisword: Displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18-letteronly: Displays all lines of the file /etc/ssh/sshd_config starting with a letter.
19-AZ: Replaces all characters A and c from input to Z and e respectively.
Usage
To use these scripts, navigate to the directory containing the script you want to use and run the script using the command line. For example, to use the 0-hello_world script, you would navigate to the directory containing the script and run the command ./0-hello_world.

Contributing
Contributions to these scripts are welcome. Please open a pull request with your changes.

License
These scripts are released under the MIT License. See the LICENSE file for more information.


