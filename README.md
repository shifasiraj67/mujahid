# github-login
Trying out selenium in java with [ChromeDriver](https://chromedriver.storage.googleapis.com/index.html) (download the right version for your laptop)
## clone git repo
` git clone https://github.com/NubeEra-MCO/Mvn-Selenium-GithubLogin-AllRepo.git `
## Change Directory
`cd Mvn-Selenium-GithubLogin-AllRepo`
## Clean Old Project 
`mvn clean`
## Compile Project
`mvn compile`
## Change Directory
`cd target\classes`
## Configure Selenium Library using classpath evnironment variable
`set classpath=%classpath%;/path/to/set/jarfiles/selenium-server-4.9.1.jar;`
## Run Project
`java gh.login.App`

## Pass Parameter to access all repositories

Enter Your Login: mujahed85
Enter Your password: *****
it will display in background all your repositories

More functions will be added later.