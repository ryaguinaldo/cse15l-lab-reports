# Lab Report 4

## Login to SSH Server
Logged in to the ssh server using the command `ssh cs15lwi23ava@ieng6.ucsd.edu` press `<enter>` and typed in my password and pressed `<enter>`.

![Screenshot 2023-03-13 193715](https://user-images.githubusercontent.com/122580027/224878672-e0bc9121-3a35-42d2-be8e-4be145f8e1eb.png)

## Clone the Forked Repository
Typed `git clone https://github.com/ryaguinaldo/lab7` and pressed `<enter>`

![Screenshot 2023-03-13 195819](https://user-images.githubusercontent.com/122580027/224881717-f9659457-6db2-4dc8-bf4f-126c11b0936c.png)

## Running the Tests to Demonstrate Failure
Typed `ls` and pressed `<enter>` to see the list of directories and files.
Then typed `cd lab7` and pressed `<enter>` to change the directory to the cloned repository.
Pressed `<up><up><enter>` to see the list of directories and files.

![Screenshot 2023-03-13 200732](https://user-images.githubusercontent.com/122580027/224882892-9e099e9d-7fbf-4295-ab87-eb3c05d3a36f.png)

I went to the [Week 3 repository](https://ucsd-cse15l-w23.github.io/week/week3/) and copied the compile command for Mac Users by highlighting the first command then pressing `<ctrl-c>`.
Then I typed `<ctrl-shift-v>` and pressed `<enter>` to paste it on my terminal.
Then I went back to the repository to copy the run command for Mac Users by highlighting the second command then pressing `<ctrl-c>`.
Then I typed `<ctrl-shitf-v>` and pressed `<enter>` to paste it on my terminal.

![image](https://user-images.githubusercontent.com/122580027/224884227-89479fdd-ed22-4978-8691-4ca95f4f9272.png)
You can see the that after running the tests, there was one failure.

## Edit the Code to Fix the Failing Test
Typed the code `nano ListExamples.java` and pressed `<enter>`.
After finding the location of the error (highlighted in yellow), I pressed `<down>` until I reached the required line and changed it from "index1" to "index2".
Then I pressed `<ctrl-o><enter><ctrl-x>` to save the changes and exit.

![Screenshot 2023-03-13 203341](https://user-images.githubusercontent.com/122580027/224886740-4a46d505-79f8-4712-994e-43c1608a176d.png)

## Run the Tests to Demonstrate Succession
Pressed `<up><up><up><enter>` to compile the file and pressed `<up><up><up><enter>` to run the test.

![Screenshot 2023-03-13 204212](https://user-images.githubusercontent.com/122580027/224887652-e8f05ac5-ed29-418e-9a96-8124ce6a8d34.png)

## Commit and Push Resulting Change to Github Account
Typed the code `git add ListExamples.java` and pressed `<enter>`
Then typed `git commit -m "PASSED" <enter>` and then `git push <enter>` to commit and push the changes made to Github

![Screenshot 2023-03-13 205136](https://user-images.githubusercontent.com/122580027/224889094-33bacdbf-c9a7-4672-bbf2-6add9b025462.png)
