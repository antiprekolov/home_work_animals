# home_work_animals

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>animals</title>
</head>
<style>

</style>
<body>

</body>
<script>
	class Animal{
		constructor(species, age, color, weight){
			this.species = dog;
			this.age = 2;
			this.color = color;
			this.weight = 5;
		}
		
		sayHello(){
			console.log(`Hi ${this.species}, ${this.age}, ${this.color}, ${this.weight}!`)
		}
	}
	class Cat extends Animal{
		constructor(breed, isIndoor){
			this.breed = breed;
			this.isIndoor = true;
		}
		meow(){
			console.log('meow meeow meow!')
		}
	}
	class Dog extends Animal{
		constructor(breed, isFriendly){
			this.breed = breed;
			this.isFriendly = true;
		}
		bark(){
			console.log('woof woof!')
		}
	
	}
	let animals = [
		new Dog('shepherd dog'),
		new Dog('pit bull'),
		new Dog('pug'),
		new Cat('sphinx'),
		new Cat('bengal'),
		new Cat('maine coon')
	]
	
	for (let value of animals){
		console.log(value);
		console.log(sayHello);
		console.log(meow);
		console.log(bark);
	}
</script>
</html>
