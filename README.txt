Commandes pour utiliser un repo en ligne :

	Récupérer un projet git et son contenu
		git clone git@github.com:Dinath/mokime.git
	Lier un dépôt local et un dépôt en ligne 
		git remote add origin git@github.com:Dinath/mokime.git
	Mettre en ligne le code
		git push -u origin master
	Si jamais ça marche pas :
		git push -u origin master --force

	Supprimer un dépôt en ligne :
		git remote remove origin	