#Studio 7
## Applying Terminal Commands  


**find . -name "ora(star)"** = search for file with name starting "ora". *is a wildcard, takes the place of stuff  
**grep "Moby Dick" file.txt** = look for "Moby Dick" in file.txt  
**wc file.txt** = lines, words, characters in file.txt  
**grep "orange" oranges.txt | wc** = lines, words, characters ONLY in lines that contain "orange"  
**sort oranges.txt | uniq -c** = sort alphabetically and then count unique  line instances  
**sed -i 's/day/night/' 24hr.txt** = substitute day into night in 24hr.txt, -i replaces all 'day's with 'night's  

**Assignment**  
analyze treatemnt of gender in Moby Dick. Create new directory. wget moby dick. make file male, write down male words in file. make file female, write down female words. grab context of male make new file, grab context of female make new file. get rid of common english words in each file. left with noncommon english words in each. then sort and count. Use sed manual. grep manual. 

weasel word. use my writing check clarity. create directory. copy three pieces of my work into dir. convert to plain text. make list of files of three weasel words. write script that replaces weasel words with something else, like a space. 