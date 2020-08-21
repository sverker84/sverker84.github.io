## Sverker's road to InfoSec

### Over The Wire
```bash
echo "ssh -p 2220 $1@bandit.labs.overthewire.org" > conn2otw.sh
chmod 755 conn2otw.sh
./conn2otw.sh bandit0

#### Challenge 5 (bandit5)
```bash
find . -type f -size 1033c \! -executable -exec file '{}' \;

#### Challenge 6 (bandit6)
```bash
find / -type f -size 33c -group bandit6 -user bandit7 2>/dev/null

#### Challenge 7 (bandit7)
```bash
grep -e "millionth" data.txt

#### Challenge 8 (bandit8)
```bash
sort data.txt | uniq -u

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR