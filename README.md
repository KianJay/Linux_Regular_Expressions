# Linux_Regular_Expressions
Linux_Regular_Expressions

<h1>Exercises 1~2</h1>
“datafile” for the exercises 1~2. you can download here
northwest NW Charles Main  3.0 .98 3 34
western  WE Sharon Gray  5.3 .97 5 23
southwest SW Lewis Dalsass  2.7 .8 2 18
southern SO Suan Chin  5.1 .95 4 15
southeast  SE Patricia Hemenway 4.0 .7 4 17
eastern  EA TB Savage  4.4 .84 5 20
northeast  NE AM Main Jr.  5.1 .94 3 13
north  NO Margot Weber  4.5 .89 5  9
central  CT  Ann Stephens  5.7 .94 5 13

<h2>Questions 1</h2>
Solve the problems using “grep”
Find the lines starting with “n”
2. Find the lines ending with 4
3. Find “TB Savage”
4. Find the lines with “5.”
5. Find the lines starting with “w” or “e”
6. Find the lines that do not contain “M”
7. Find the lines that contain two uppercase letters followed by one space and one uppercase letter.
8. Find the lines where “s” repeats more than once
<h2>Answers 1</h2>
<p> # grep '^n' datafile</p>
# grep '4$' datafile
# grep 'TB Savage' datafile
# grep '5\.' datafile
# grep '^[we]' datafile
# grep -v 'M' datafile
# grep '[A-Z][A-Z] [A-Z]' datafile
# grep 'ss*' datafile
</br>
<img src="https://user-images.githubusercontent.com/54985943/112938587-dae30400-9164-11eb-9ee2-3f3130a4a75b.png" alt='regex'/>
</br>
<h2>Questions 2</h2>
Solve the problems using “egrep”</br>
1. Find NW or EA pattern</br>
2. Find “3” where it repeats more than once</br>
3. Find the lines that contain 2.x or 2x pattern (x is number)</br>
4. Find the lines that contain “no” pattern where it repeats more than once</br>
5. Fine the lines with “Sh” and “Su”</br>
<h2>Answers 2</h2></br>
# egrep '(NW|EA)' datafile</br>
# egrep '3+' datafile</br>
# egrep '(2\.?[0-9])' datafile</br>
# egrep '(no)+' datafile</br>
# egrep 'S(h|u)' datafile</br>

<img src="https://user-images.githubusercontent.com/54985943/112938576-d585b980-9164-11eb-96ef-aa63c9054f5e.png" alt='regex'/>
