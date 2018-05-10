# Day 28

## Présentation du programme:
Le programme a été fait par Quentin, Abdel, Alexandra & Selma. 

#### Lien Heroku : https://

## Mission:

Faire une landing page du site https://www.thehackingproject.org , et promouvoir ce dernier.


## Les étapes 


#### La landing page ✅
Pour créer notre landing page, nous avons repris une template bootstrap en suivant les étapes suivantes:
	 Dans le Gemfile
	```
	gem 'frontend-generators'
	```
	 Dans le Rakefile
	```
	require "frontend_generators"
	load 'tasks/add_assets.rake'
	```
	Pour ajouter le fichier Bootstrap à l'app Rails, il faut entrer dans la commande 
	```
	bundle exec rake add_assets:bootstrap
	```

	Dans  le fichier ``` application.css```
	```
	*= require bootstrap
	```

	Dans  le fichier ``` application.js```
	```
	//= require bootstrap
	```



#### Le call to action ✅

#### L'acquisition ✅

#### Analyse des metrics ✅

#### Le rendu ✅




## Installation

Une fois le repo cloné, fais ces commandes pour installer les gems et lancer le projet sur ton serveur local :


```
bundle install 
```

```
rails db:migrate 
```

```
rails s
```


## Pré-requis

Projet libre de droit et d'accès à la lecture/écriture. Pour pouvoir visualiser le projet, un simple navigateur suffit.
```
Firefox, Safari, Chrome, Internet Explorer 8, ...
```









## Contributeurs:


