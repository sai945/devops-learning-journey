# Linux - Basic Commands

| Command | Purpose |
|---|---|
| whoami | Displays current username |
| hostname | Displays machine hostname |
| date | Displays current date and time |
| uname | Displays kernel information |
| uname -s | Displays kernel name |
| uname -a | Displays complete kernel information |
| echo | Prints text |
| pwd | Displays current directory |
| ls | Lists files and directories |
| cat | Displays file contents |
| mkdir | Creates a directory |
| mkdir -p | Creates nested directories |
| cd | Changes directory |
| cd .. | Moves to parent directory |
| cd ~ | Moves to home directory |
| clear | Clears terminal screen |

## Command Examples

### User information

whoami

### Hostname

hostname

### Date and time

date

### Kernel information

uname -s
uname -a

### Print text

echo "Hello Linux"

### Current directory

pwd

### List files

ls
ls /
ls /etc

### Read files

cat /etc/hostname
cat /etc/os-release

### Create directories

mkdir notes

mkdir -p projects/api/src

### Navigate directories

cd /etc
cd ..
cd ~
cd notes

### Redirect output

whoami > user.txt
hostname > host.txt
date > when.txt

### Read redirected output

cat user.txt
cat host.txt
cat when.txt

## Important Notes

- > overwrites existing file contents.
- Use Tab for command and path completion.
- Use Up Arrow to access command history.
- Use Ctrl + C to interrupt a running command.