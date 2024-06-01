- production (real production branch)
	- hotfix (branches that are quick fixes on production)
- staging (blue/green - duplicate of the production environment and if it all passes tests will swap it with production)
- main (main branch where we are going to merge all our features)
	- features
- qa (perform tests before merging into staging)

# Updates
This is just a normal updates

# My Name Lol
```js
// this is my actualy real data, it just contain my First Name and Last Name
const myData = {
	firstName: Siddhant,
	lastName: Singh
}

/**
* This is just bakchodi, i just want to use Bind method here.. nothing serious
*/
const methods = {
	sayMyName: function(){
		console.log(`Hey My name is ${this.firstName} ${this.lastName}`)
	}
}
// create a copy of that method and then will call to yk say my name lol
const okNowIWillSayMyName = methods.sayMyName.bind(myData)
okNowIWillSayMyName()
```
