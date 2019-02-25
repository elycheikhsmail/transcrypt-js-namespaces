# Transcrypt IDE autocomplete for js native object in python code

Transcrypt est la meilleur solution pour  develloper cote client avec en python puis traduir le code en js.

mais le probleme qui se pose que on perd l'appui des IDE (VSC ) lorsque on accede a un object comme document , window ,alert ...

la solution que je propose est des creer des "interfaces"  en python qui permette 
a  IDE (VSC )  de reconnaintre et comprendre la sructure et la nature  des objects relalive a DOM ou BOM 

la fonction `__pragma__ `  permet de saauter le bloc  <br>
entre  `#__pragma__ ("skip") `et  `#__pragma__ ("skip") `<br>
qui contidra l'import de nos interfaces py

telechager le code et juger par vous meme