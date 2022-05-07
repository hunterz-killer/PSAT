# PSAT
PSAT Solved Programs List


| S No |	CF Question	| Title | Solution Link |
|---|---|---|---|
|	1	|	https://codeforces.com/problemset/problem/4/A	|	Watermelon	|	[Solution](https://codeforces.com/contest/4/submission/134878204) |
|	2	|	https://codeforces.com/problemset/problem/50/A	|	Domino piling	|	[Solution](https://codeforces.com/contest/50/submission/134969321) |
|	3	|	https://codeforces.com/problemset/problem/59/A	|	Word	|	[Solution](https://codeforces.com/contest/59/submission/143396484) |
|	4	|	https://codeforces.com/problemset/problem/96/A	|	Football	|	[Solution](https://codeforces.com/contest/96/submission/144506243) |
|	5	|	https://codeforces.com/problemset/problem/231/A	|	Team	|	[Solution](https://codeforces.com/contest/231/submission/155910714) |
|	6	|	https://codeforces.com/problemset/problem/236/A	|	Boy or girl	|	[Solution](https://codeforces.com/contest/236/submission/135061159) |
|	7	|	https://codeforces.com/problemset/problem/365/A	|	Good number	|	[Solution](https://codeforces.com/contest/365/submission/146332138) |
|	8	|	https://codeforces.com/problemset/problem/427/A	|	Police	|	[Solution](https://codeforces.com/contest/427/submission/145849371) |
|	9	|	https://codeforces.com/problemset/problem/617/A	|	Elephant	|	[Solution](https://codeforces.com/contest/617/submission/146311799) |
|	10	|	https://codeforces.com/problemset/problem/754/A	|	Lesha	|	[Solution](https://codeforces.com/contest/754/submission/156057477) |
|	11	|	https://codeforces.com/problemset/problem/791/A	|	Bear	|	[Solution](https://codeforces.com/contest/791/submission/136566843) |
|	12	|	https://codeforces.com/problemset/problem/798/A	|	Mike	|	[Solution](https://codeforces.com/contest/798/submission/141391975) |
|	13	|	https://codeforces.com/problemset/problem/831/A	|	Unimodal	|	[Solution](https://codeforces.com/contest/831/submission/144327181) |
|	14	|	https://codeforces.com/problemset/problem/935/A	|	Fafa	|	[Solution](https://codeforces.com/contest/935/submission/137297203) |
|	15	|	https://codeforces.com/problemset/problem/954/A	|	Diagonal	|	[Solution](https://codeforces.com/contest/954/submission/143322874) |
|	16	|	https://codeforces.com/problemset/problem/1008/A	|	Romaji	|	[Solution](https://codeforces.com/contest/1008/submission/136444649) |
|	17	|	https://codeforces.com/problemset/problem/1017/A	|	Rank	|	[Solution](https://codeforces.com/contest/1017/submission/137133442) |
|	18	|	https://codeforces.com/problemset/problem/1030/A	|	Easy problem	|	[Solution](https://codeforces.com/contest/1030/submission/135285337) |
|	19	|	https://codeforces.com/problemset/problem/1031/A	|	Golden Plate	|	[Solution](https://codeforces.com/contest/1031/submission/156063464) |
|	20	|	https://codeforces.com/problemset/problem/1061/A	|	Coins	|	[Solution](https://codeforces.com/contest/1061/submission/144492929) |
|	21	|	https://codeforces.com/problemset/problem/1076/A	|	Minimize	|	[Solution](https://codeforces.com/contest/1076/submission/141458899) |
|	22	|	https://codeforces.com/problemset/problem/1077/A	|	Frog Jump	|	[Solution](https://codeforces.com/contest/1077/submission/134863512) |
|	23	|	https://codeforces.com/problemset/problem/1088/A	|	Ehab & another construction	|	[Solution](https://codeforces.com/contest/1088/submission/146319208) |
|	24	|	https://codeforces.com/problemset/problem/1093/A	|	Dice	|	[Solution](https://codeforces.com/contest/1093/submission/156065509) |
|	25	|	https://codeforces.com/problemset/problem/1095/A	|	Repeat	|	[Solution](https://codeforces.com/contest/1095/submission/142010733) |
|	26	|	https://codeforces.com/problemset/problem/1111/A	|	Superhero	|	[Solution](https://codeforces.com/contest/1111/submission/141450889) |
|	27	|	https://codeforces.com/problemset/problem/1146/A	|	Love 'A'	|	[Solution](https://codeforces.com/contest/1146/submission/143395771) |
|	28	|	https://codeforces.com/problemset/problem/1335/A	|	Candies	|	[Solution](https://codeforces.com/contest/1335/submission/156068335) |
|	29	|	https://codeforces.com/problemset/problem/1351/A	|	A+B (Trial Problem)	|	[Solution](https://codeforces.com/contest/1351/submission/136796200) |
|	30	|	https://codeforces.com/problemset/problem/1511/A	|	Review	|	[Solution](https://codeforces.com/contest/1511/submission/145365929) |
|	31	|	https://codeforces.com/problemset/problem/1512/A	|	Spy	|	[Solution](https://codeforces.com/contest/1512/submission/145366372) |
|	32	|	https://codeforces.com/problemset/problem/1593/A	|	Elections	|	[Solution](https://codeforces.com/contest/1593/submission/137310106) |

# Mock Exam Solutions

The Winner

```
for _ in range(int(input())):
    a, b = map(int, input().split())
    if a>b:
        print("A", a-b)
    else:
        print("B", b-a)
```
Odd Divisible

```
n, k = map(int, input().split())
res = 0
for i in range(k,n,k):
    if i%2!=0:
        res+=1
        
print(res)
```

Increasing Digits 

```
ui = int(input())
if len(str(ui))==1:
    print("YES")

elif str(ui).count(str(ui)[0]) != len(str(ui)):
    req = list(map(str, str(ui).strip()))
    req.sort(reverse=True)


    req = "".join(req)

    if str(ui) == req:
        print("YES")
    else:
        print("NO")
else:
    print("NO")
```

Strange Grid Again

```
def strangeGrid(r, c):
    d,m = divmod(r-1,2)
    a = d*10+2*c
    a -= 1 if m else 2
    return a

r,c = map(int,input().split())
print(strangeGrid(r, c))
```

Palindrome

```
a , b = map(str, input().split())
r_b = b[::-1]
res = "YES"
for x in range(min(len(a), len(b))):
    if a[x]!=r_b[x]:
        res = "NO"
        break
print(res)
```
