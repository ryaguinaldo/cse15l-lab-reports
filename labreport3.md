# CSE 15L Lab Report 3

`grep -ri "str" <text file pattern>` - `grep -ri` does a recursive search of a string from a file pattern. The difference when using this command with just `grep` is that it can search within the directories and not just one file. It also includes the filenames of where the search has occurred. The -i after -r makes it so that it's not case-sensitive. The asterisk, `*`, means all the arguments passed to the script or function.grep
This can be used to look for a string within the files of a directory.

   ex. `grep -ri "california" *` shows:
  
  ![Screenshot 2023-02-27 233849](https://user-images.githubusercontent.com/122580027/221786137-b4ce5ee0-42a3-4bf5-9622-ca1eea254236.png)
  
  ex. `grep -ri "san diego" *` shows:
  
  ![Screenshot 2023-02-27 234011](https://user-images.githubusercontent.com/122580027/221786027-9e331585-0823-4412-9517-a0dbfb6cde1b.png)

---

`grep -rl "str"` - This command does a recursive search of a string from a file pattern but only prints the filenames. The difference when using this command with just `grep` is that it can be used to search within the directory and prints out the filenames instead of showing the texts where it was found.  
This can be used to consolidate and clean up the results by printing only the filenames where the string belongs.

   ex. `grep -rl "California"`
    
   ![Screenshot 2023-02-13 211206](https://user-images.githubusercontent.com/122580027/218645208-4787b59c-0192-47bf-95a4-524056ce8226.png)
  
   ex. `grep -rl "San Diego"`
   
   ![Screenshot 2023-02-13 212246](https://user-images.githubusercontent.com/122580027/218646702-14ba89a8-482a-4dfc-9fb2-daa039dc2d20.png)

---

`grep -n "str" <text file pattern>` - This command prints the line number of the text file that contains the string. 
This can be useful for those trying to reference a specific line by using a string.

  ex. `grep -n "California" ./written_2/travel_guides/berlitz2/California-WhereToGo.txt`
  
  ![Screenshot 2023-02-13 212445](https://user-images.githubusercontent.com/122580027/218646991-231d6f2d-aa03-4f3d-a84b-417651743e5f.png)
  
  ex. `grep -n "San Diego" ./written_2/travel_guides/berlitz2/California-WhereToGo.txt`
  
  ![Screenshot 2023-02-13 212847](https://user-images.githubusercontent.com/122580027/218647640-ed1c2890-81a5-4171-bc90-3a1aee420b05.png)

---

`grep -c "str" <text file pattern>` - This command prints the occurences of the string. 
This can be useful if you need to provide the number of times a word or a sentence has occurred.

  ex. `grep -c "California" ./written_2/travel_guides/berlitz2/California-WhereToGo.txt`
  
  ![image](https://user-images.githubusercontent.com/122580027/218648467-e3255972-9ac8-48b2-8956-84063b43adf5.png)

  ex. `grep -c "San Diego" ./written_2/travel_guides/berlitz2/California-WhereToGo.txt`
  
  ![Screenshot 2023-02-13 213657](https://user-images.githubusercontent.com/122580027/218648744-3ad8e1bf-9880-46c0-8b83-4f5ffa5e71a1.png)

