# LPIC1: Personal cheatsheet
_**Notes from course: LPIC1 - instructor: Peyman Hooshmandi Raad**_

## title

```bash
# Example
# $ sort < temp.txt | uniq -c | sort -nr
#  5 mina
#  3 ali
#  2 sara
#  2 reza
#  2 keyvan
#  1 jafar

sed 's/old/new/'        # it replaces first old word of each line wiith new like vim 
sed 's/old/new/g'       # it replaces globaly
sed -E 's/old/new/'     # it support regex
```
## Mounting block devices
```bash
# dd # read directly from block device (0001111...)

