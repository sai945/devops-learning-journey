# Linux - Practical Tasks

## Task 1: Collect Machine Information

### Objective

Create /root/answers and collect machine information
in five separate text files.

### Solution

mkdir -p /root/answers

cd /root/answers

whoami > user.txt

hostname > host.txt

uname -s > kernel.txt

ls / > root-listing.txt

cat /etc/os-release > os.txt

### Verify the files

ls -l /root/answers

cat user.txt
cat host.txt
cat kernel.txt
cat root-listing.txt
cat os.txt

### Expected files

/root/answers/user.txt
/root/answers/host.txt
/root/answers/kernel.txt
/root/answers/root-listing.txt
/root/answers/os.txt

---

## Task 2: Prepare a Working Folder

### Objective

Create /root/work and collect user, date and hostname
information.

### Solution

mkdir -p /root/work

cd /root/work

whoami > me.txt

date > today.txt

hostname > here.txt

### Verify

cat me.txt

cat today.txt

cat here.txt

### Expected files

/root/work/me.txt
/root/work/today.txt
/root/work/here.txt

## What I Learned

- Creating directories with mkdir.
- Navigating using cd.
- Collecting system information.
- Redirecting command output using >.
- Reading saved information using cat.