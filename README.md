## IEEE Git WorkShop

#### Steps:

* Create a new issue.
    eg: Adding Nityananda Gohain in participants

* Chekout a new branch 
    eg: `git checkout -b newbranch" 

    replace `newbranch` with something like "fixing issue `#yourissuenumber`

* change the code.
    eg: In the participants array  add a new object :
    ````
    {
        name: "",
        photo: "",
        message: "",
        github: "",
        facebook: "",
        email: "",
    },
    ````

* add your file to the staging area
    eg: `git add index.html`

* commit your file 
    eg: `git commit -m "your commit message"`

* Now push your code to the forked repository.
    eg: `git push origin your_branch_name`