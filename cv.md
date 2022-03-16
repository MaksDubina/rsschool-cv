# Maksim Dubina

## Contaks

- *Location:* Novosibirks, Russia
- *Discord:* Glower #8711
- *Phone:* +7-953-762-48-40
- *Email:* mgd8832@gmail.com
- *GitHub:* [MaksDubina](https://github.com/MaksDubina)
## About Me

## Skills
- *HTML*
- *CSS*
- *JavaScript*
- *Python*

## Code Example
**Silicon Valley:** Artificial intelligence Anton, created by Gilfoyle, has hacked a network of smart refrigerators. Now he's using them as servers for the "Pied Piper". Help the owner of the company find all the infected refrigerators.

For each refrigerator there is a line with data consisting of lowercase letters and numbers, and if it contains the word "anton" (not necessarily adjacent letters, the main thing is the presence of a sequence of letters), then the refrigerator is infected and you need to display the number of the refrigerator, numbering starts from one

**Input format:** The first line contains the number n - the number of refrigerators. The following n lines contain strings containing Latin lowercase letters and numbers, each line contains from 55 to 100100 characters.

**Output format:** The program should display the numbers of infected refrigerators separated by a space. If there are no such refrigerators, nothing needs to be displayed.

```
list1 = [ input() for i in range(int(input()))]
total = []
for i in range(len(list1)):
    flag = 1
    for j in 'anton':
        if j in list1[i]:
            index = list1[i].find(j)
            list1[i] = list1[i][index:]
        else:
            flag = 0
    if flag:
        total.append(i+1)
print(*total)
```

## Experience

## Education