layout: page
title: "Sverker"
permalink: /

## Sverker's road to InfoSec

### Over The Wire
```shell
echo "ssh -p 2220 $1@bandit.labs.overthewire.org" > conn2otw.sh
chmod 755 conn2otw.sh
./conn2otw.sh bandit0
```

#### Challenge 5 (bandit5)
```shell
find . -type f -size 1033c \! -executable -exec file '{}' \;
```

#### Challenge 6 (bandit6)
```shell
find / -type f -size 33c -group bandit6 -user bandit7 2>/dev/null
```

#### Challenge 7 (bandit7)
```shell
grep -e "millionth" data.txt
```

#### Challenge 8 (bandit8)
```shell
sort data.txt | uniq -u
```

#### Challenge 9 (bandit9)
```shell
strings data.txt | grep '=='
```

#### Level 10
```shell
base64 -d data.txt
```

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
