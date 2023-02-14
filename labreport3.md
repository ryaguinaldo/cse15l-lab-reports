# CSE 15L Lab Report 3

`grep -r "str" <text file pattern>` - This command searches a directory that includes the specific string you're looking for.
This can be used to look for a word within a text file of a directory.

   ex. `grep -r "California" ~/skill-demo1-data/written_2/travel_guides/berlitz2/California-WhereToGo.txt` shows:
  
  ![Screenshot 2023-02-13 212050](https://user-images.githubusercontent.com/122580027/218646429-45204998-6b5b-43da-8946-5d7f2dc3f8b0.png)
  
  ex. `grep -r "San Diego" ./written_2/travel_guides/berlitz2/California-WhereToGo.txt` shows:
  
  ![Screenshot 2023-02-13 211932](https://user-images.githubusercontent.com/122580027/218646270-d5f94463-1cab-4ffe-b0df-e9f473bfbfc7.png)

---

`grep -rl "str"` - This command shows all of the text files that contains the specific string. 
This can be used to search files that contains a word you're looking for.

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

