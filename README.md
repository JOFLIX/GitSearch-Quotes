# GitSearch

GitSearch is simply an Angular App that uses Github API to retrieve user data. Submit a username and it gives you repository details of the user, including number of repositories, commits and branches and also when it was last updated.

## Requirements

Both the CLI and the project have dependecies that require Node together with NPM. So make sure you have these installed and working before proceeding.

##### Technologies Used

- This project was generated with Angular CLI version 7.1.4.
- HTML & CSS (Bootstrap)

##### Setup Instructions and Installation

- Clone this repository to a location in your file system.
- Open terminal command line then navigate to the root folder of the application.
- Run `ng serve` command.
- Navigate to `http://localhost:4200/` in your browser.


## Behaviour Driven Development

1. Displays GitHub info of a user when user name is entered
   - INPUT: "user name entered"
   - OUTPUT: "Displays User Details"
2. Displays all repositories of a user when show repositories button is pressed
   - INPUT: "Show repositories button pressed
   - OUTPUT: "Displays User Repo Details"
3. Displays an error message if you leave the name input field blank
   - INPUT: " " 
   - OUTPUT: "Name's required" 
4. Displays an error message if you leave the repo name input field blank
   - INPUT: " " 
   - OUTPUT: "Repo Name is required"
5. Displays an error message if the user name entered couldn't be found
   - INPUT: "username"
   - OUTPUT: "User Doesn't Exist"
6. Displays an error message if the repo name entered couldn't be found
   - INPUT: "repository" 
   - OUTPUT: "Repository Doesn't Exist"


## Development

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:
- Fork the repo
- Create a new branch (git checkout -b improve-feature)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (git commit -am 'Improve feature')
- Push to the branch (git push origin improve-feature)
- Create a Pull Request


## Known Bugs

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue here by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.

##### Link to Live Site : [https://yomzsamora.github.io/GitSearch/](https://yomzsamora.github.io/GitSearch/)

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
