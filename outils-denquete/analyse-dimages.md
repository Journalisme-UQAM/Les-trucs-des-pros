---
description: >-
  Qui, quoi, où? On peut répondre à ces questions grâce à la recherche inversée
  d'images.
---

# 📸 Analyse d'images

## Métadonnées <a href="#3149" id="3149"></a>

Ce devrait être votre premier réflexe.

Pensez d'abord à consulter les métadonnées d'une image. Parfois, vous y trouverez la réponse à: _**«Où diable cette photo a-t-elle été prise?»**_

<figure><img src="../.gitbook/assets/metadonnees.png" alt="" width="563"><figcaption></figcaption></figure>

Quand les métadonnées sont muettes, vous pouvez vous tourner vers l'un ou l'autre des outils suivants.

## Recherche d'images inversée <a href="#3149" id="3149"></a>

Quatre outils de recherche d'images inversée peuvent être utiles.

* **TinEye**, le plus ancien, ne va que vous permettre de retrouver exactement l'image que vous lui soumettez. [https://tineye.com](https://tineye.com)
* **Google Lens** est souvent très bon, mais il est davantage conçu comme un outil pour nous aider à magasiner, donc il va parfois focaliser sur les vêtements que la personne porte ou les objets autour plutôt que de nous dire qui apparaît sur la photo ou où est-ce qu'on se trouve.
* **Bing images** peut parfois s'avérer une bonne solution de rechange à Google. https://www.bing.com/visualsearch
* Le volet images du moteur de recherche russe **Yandex** peut également être utilisé si les deux précédents ne donnent pas les résultats escomptés.

### Qui est sur la photo?

J'ai soumis une photo intitulée _dude.jpg_. C'est Google Lens qui a le mieux reconnu le recteur de l'UQAM.

<figure><img src="../.gitbook/assets/pallage.png" alt=""><figcaption><p>Google Pallage a reconnu M. Image</p></figcaption></figure>

### Qu'est-ce que c'est?

J'ai soumis une image appelée _egliz.jpg_ et Google Lens a été l'outil qui a réussi à identifier précisément de quelle bâtiment il s'agissait.

<figure><img src="../.gitbook/assets/megantic.png" alt=""><figcaption><p>Église Sainte-Agnès, située au centre-ville de Lac-Mégantic.</p></figcaption></figure>

J'ai par contre soumis une autre image appelée _metro.jpg_. Tous les outils ont eu de la difficulté. Même Google Lens a incorrectement identifié l'immeuble se trouvant derrière, immeuble qui n'a même pas été conçu par le même architecte... Dans les autres résultats, cependant, on trouve la bonne réponse.

<figure><img src="../.gitbook/assets/vanderrohe.png" alt=""><figcaption><p>Un des immeubles du complexe Westmount Square, construit en 1967 et conçu par le célèbre architecte Mies Van der Rohe.</p></figcaption></figure>

### Où suis-je?

Mise en situation. Vous faites enquête sur une influenceuse en cavale. Vous trouvez cette photo sur Instagram. Où a-t-elle été prise? Ici encore, Google Lens est celui qui réussit le mieux à reconnaître le paysage en arrière plan.

<figure><img src="../.gitbook/assets/tremblant.png" alt=""><figcaption><p>Notre influenceuse est à Tremblant avec une groupie.</p></figcaption></figure>

## Analyse criminalistique (_forensic_)

Pour savoir si on a affaire à une image manipulée (par modification avec Photoshop, par exemple) ou générée par un système basé sur l'IA, on peut en effectuer l'analyse à l'aide de Forensically.

Son outil «_**Clone detection**_» permet de repérer les zones où il y a eu du copier-coller.

Les images générées par IA ont tendance à avoir plus de ces zones que les images réelles. Voici deux exemples avec des images générées par Midjourney dont le réalisme est à s'y méprendre.

Comparez toujours avec des images dont l'authenticité ne fait pas de doute et examinez-les avec les mêmes paramètres.

<div>

<figure><img src="../.gitbook/assets/forensicVrai2.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/forensicFaux1.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/forensicVrai1.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/forensicFaux2.png" alt=""><figcaption></figcaption></figure>

</div>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*YNM1pizIOxqXQgU1MjPqxw.png" alt="" height="482" width="700"><figcaption></figcaption></figure>

L’outil [**Forensically**](https://29a.ch/photo-forensics/) permet de faire l’analyse poussée d’une image, permettant de détecter des zones où il y a eu du copier-coller et d’afficher facilement les métadonnées d’une image.

De son côté, [**Google Lens**](https://www.google.ca/imghp?hl=fr) peut être redoutablement efficace pour identifier une personne dans une photo que vous lui soumettez. Voici un exemple avec le recteur de l'UQAM.

Mais souvent, il pense qu'on cherche un produit plutôt qu'une personne...

<figure><img src="../.gitbook/assets/jhr.png" alt=""><figcaption><p>Je ne suis qu'une chemise</p></figcaption></figure>

Le volet images du moteur de recherche russe [**Yandex**](https://yandex.com/images/) peut parfois réussir là où Google échoue.
