# HackerRank Plugin
Run code from Sublime Text for HackerRank problems.  

# Required Dependencies

* Sublime Text have to use python 3
* Python [request](https://github.com/kennethreitz/requests) module
* Cookies have to set in HackerRank.sublime-settings in the package location `~/LibraryApplication Support/Packages/HackerRank/`


# Sublime Settings

* HackerRank.sublime-settings contains default language, and debug settings.
* We need to set the Cookie and CSRF-Token to authenticate.
* The url of the problem you are solving have to be set in Problem key in settings

```json
{
	"Cookie" : "cookie-copied-from-login-response"
	"CSRF-Token" : "CSRF-Token-To-Authenticate",
	"Language" : "python",
	"Debug" : true
	"Problem" : "https://www.hackerrank.com/rest/contests/master/challenges/simple-array-sum/compile_tests"	
}
```