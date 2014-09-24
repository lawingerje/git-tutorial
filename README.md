git-tutorial
============

##Tutorial

1. Fork this tutorial 

###Basic Setup

1. Navigate to the repository on GitHub
2. Copy the clone URL
3. Open command line
4. cd to your working directory
5. enter `git clone https://github.com/<Your Username Here>/git-tutorial.git` This will be the url you copied in step 2
6. cd into the project directory `cd git-tutorial`

###Add A File

1. Create a new file in the project directory. Name it `new.cpp`
2. Copy this code into the file:
```
int main() {
	cout << "Hello World!";
	return 0;
}
```
3. In the command line type `git status`. You will see that the file `new.cpp` is currently untracked and needs to be added to git.
4. Type `git add new.cpp` to add the file to git
5. Run `git status` again and note that `new.cpp` is now ready to be commited.
6. Commit files to git with `git commit -m "Added new.cpp"`
You have not actually yet pushed the file back to github. Git stores the repository locally on your machine, but can also push your changes back to github
7. Push your changes to github by running the command `git push`
You will be prompted for your github username and password.