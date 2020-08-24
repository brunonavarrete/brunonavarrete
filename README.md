```js

	/* open up you js console and check out my hobbies */

	class WebDeveloper {
		constructor(fullName, fuel, hobbies) {
			this._fullName = fullName
			this._fuel = fuel
			this._hobbies = hobbies
		}
		shareHobbie() { // <<< here it is
			let index = Math.floor(Math.random() * 4) + 1  
			
			console.log( `Hey! Check out this great ${ this._hobbies[index]['name'] } :3` )
			
			setTimeout(() => {
				window.open( this._hobbies[index]['url'], '_blank' )
			},3000)
		}
	}

	const Bruno = new WebDeveloper(
		'Bruno Navarrete',
		'Coffee', 
		[
			{
				name:'Silly UK Game Show', 
				url: 'https://www.youtube.com/results?search_query=wilty' 
			},
			{
				name:'Great Audible', 
				url: 'https://www.audible.com/pd/Extreme-Ownership-Audiobook/B015TVHUA2?qid=1598298681' 
			},
			{
				name:'Show on Netflix', 
				url: 'https://www.netflix.com/title/80203144' 
			},
			{
				name:'Great Beer', 
				url: 'https://www.samueladams.com/our-beers/originals/lager/boston-lager' 
			}
		]
	)

```
---

#### Markup and Stylesheets

![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=HTML5&color=003ea0&style=for-the-badge&logo=html5&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=CSS3&color=003ea0&style=for-the-badge&logo=css3&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Sass/Scss&color=003ea0&style=for-the-badge&logo=sass&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Bootstrap%204&color=003ea0&style=for-the-badge&logo=bootstrap&logoColor=white)

#### JavaScript

![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=ES6&color=ffc52f&style=for-the-badge&logo=javascript&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Vue%20js&color=ffc52f&style=for-the-badge&logo=vue.js&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=vuetify%20&color=ffc52f&style=for-the-badge&logo=vuetify&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=React%20js&color=ffc52f&style=for-the-badge&logo=react&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=jQuery%20&color=ffc52f&style=for-the-badge&logo=jquery&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=node%20&color=ffc52f&style=for-the-badge&logo=node.js&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=npm%20&color=ffc52f&style=for-the-badge&logo=npm&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=webpack%20&color=ffc52f&style=for-the-badge&logo=webpack&logoColor=white)

#### PHP / CMS
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=php&color=silver&style=for-the-badge&logo=php&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=laravel&color=silver&style=for-the-badge&logo=laravel&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=composer&color=silver&style=for-the-badge&logo=composer&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=craft%203&color=silver&style=for-the-badge&logo=craft%20cms&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=twig&color=silver&style=for-the-badge)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=wordpress&color=silver&style=for-the-badge&logo=wordpress&logoColor=white)

#### Database
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=mysql&color=12284B&style=for-the-badge&logo=mysql&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Mongo%20db&color=12284B&style=for-the-badge&logo=mongodb&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=SQlite&color=12284B&style=for-the-badge&logo=sqlite&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=mariadb&color=12284B&style=for-the-badge&logo=mariadb&logoColor=white)

#### Other
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=linux&color=8d744a&style=for-the-badge&logo=linux&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=lamp%20stack&color=8d744a&style=for-the-badge&logo=apache&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=lemp%20stack&color=8d744a&style=for-the-badge&logo=nginx&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=mean%20stack&color=8d744a&style=for-the-badge&logo=express.js&logoColor=white)

![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=git&color=9d845a&style=for-the-badge&logo=git&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=github&color=9d845a&style=for-the-badge&logo=github&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=gitlab&color=9d845a&style=for-the-badge&logo=gitlab&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=digitalocean&color=9d845a&style=for-the-badge&logo=digitalocean&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=shopify&color=9d845a&style=for-the-badge&logo=shopify&logoColor=white)

![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=adobe%20photoshop&color=bda46a&style=for-the-badge&logo=adobe%20photoshop&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=sketch&color=bda46a&style=for-the-badge&logo=sketch&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=zeplin&color=bda46a&style=for-the-badge&logo=zeplin&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=asana&color=bda46a&style=for-the-badge&logo=asana&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=trello&color=bda46a&style=for-the-badge&logo=trello&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=slack&color=bda46a&style=for-the-badge&logo=slack&logoColor=white)

![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Analytics&color=cdb47a&style=for-the-badge&logo=google%20analytics&logoColor=white)
![forthebadge made-with-python](https://img.shields.io/static/v1?label=&message=Postman&color=cdb47a&style=for-the-badge&logo=postman&logoColor=white)



<!--
**brunonavarrete/brunonavarrete** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->