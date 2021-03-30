# Linux_Regular_Expressions
Linux_Regular_Expressions

<h1>Exercises 1~2</h1>
<img src='https://user-images.githubusercontent.com/54985943/112938908-83916380-9165-11eb-9df3-0f6f48c7ab74.png' alt="regex" />
“datafile” for the exercises 1~2. you can download here

<h2>Questions 1</h2>
Solve the problems using “grep”</br>
Find the lines starting with “n”</br>
2. Find the lines ending with 4</br>
3. Find “TB Savage”</br>
4. Find the lines with “5.”</br>
5. Find the lines starting with “w” or “e”</br>
6. Find the lines that do not contain “M”</br>
7. Find the lines that contain two uppercase letters followed by one space and one uppercase letter.</br>
8. Find the lines where “s” repeats more than once</br>
</br>
<h2>Answers 1</h2>
<p> # grep '^n' datafile</p>
- # grep '4$' datafile
- # grep 'TB Savage' datafile
- # grep '5\.' datafile
- # grep '^[we]' datafile
- # grep -v 'M' datafile
- # grep '[A-Z][A-Z] [A-Z]' datafile
- # grep 'ss*' datafile
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
<h2>Answers 2</h2>
- # egrep '(NW|EA)' datafile</br>
- # egrep '3+' datafile</br>
- # egrep '(2\.?[0-9])' datafile</br>
- # egrep '(no)+' datafile</br>
- # egrep 'S(h|u)' datafile</br>

<img src="https://user-images.githubusercontent.com/54985943/112938576-d585b980-9164-11eb-96ef-aa63c9054f5e.png" alt='regex'/>
