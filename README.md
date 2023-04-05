<!-- command Kv for live  -->


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- -->
<!-- HEADER -->
<br>
<header align="center">
   <img align="center" src="logo.png"><br/> <br/>
  <h1 align="center">Projets Data Scientist</h1>
  <p align="center">
    Descripton pour tout les projet
  </p>
</header>



<!-- TABLE OF CONTENTS -->

  <summary>Table De Matière</summary>
  <ol>
    <li>
      <a href="#about-the-project">Présentations Des Chapitres</a>
      <ul>
        <li><a href="#built-with">Langages utilisés </a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Pour Commencer</a>
      <ul>
        <li><a href="#prerequisites">Prérequis</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Remerciements</a></li>
  </ol>




<!-- ABOUT THE PROJECT -->
## Apropos Des Projets

 <br><div align="center"><img align="center" src="SKLearn.png"></div><br>

## Chapitre 1: Les Bases Du Langague Python 

Le 1er chapitre contient Les bases du langage Python.

## Chapitre 2: Calcule Numèrique: 
-*Numpy et pandas*-

Les deux packages principaux pour manipuler des données sont NumPy et Pandas. Le deuxième chapitre contient un détail de l'utilisation des trois structures de base de ces packages que sont les ndarray de NumPy et les Series et DataFrame de Pandas.


## Chapitre 3: Visualisation des données 
-*matplotlib et seaborn*-
  
De nombreux packages sont disponibles en Python pour représenter des données
de manière attractive.

**Matplotlib** est le plus connu est et sert de base à de nombreux autres packages.

**Matplotlib** est un package complet pour la data visualisation. Il est basé sur la
construction de graphiques en utilisant des commandes simples.

**Seaborn** est un autre package intéressant pour la création de graphiques. Il est basé sur Matplotlib et en utilise les principes. Son principal intérêt réside dans la création de graphiques plus spécifiques en quelques lignes de code.


## Chapitre 5: Régression Linèaire
La régression linéaire simple sert à trouver unne relation d’une variable de sortie (continue) par rapport à une autre.

- Génération de données aléatoires avec une tendance linéaire.
  
- Création de la matrice X qui contient la colonne de Biais.
  
- Finalement, création d'un vecteur parametre $\theta$, initialisé avec des coefficients aléatoires.
  
- On implémente un modele $F = X.\theta$, puis on teste le modele pour voir s'il n'y a pas de bug (bonne pratique oblige)
  
- On mesure les erreurs du modele sur le Dataset X, y en implémenterl'erreur quadratique moyenne.
  
- On implémente la formule du gradient pour la **MSE**
  
- On définit un **nombre d'itérations**, ainsi qu'un **pas d'apprentissage $\alpha$**.

- Une fois le modele entrainé, on observe les resultats par rapport a notre Dataset.

- Tracage de la courbe d'apprentissage afin de vérifier si notre algorithme de Descente de gradient a bien fonctionné, on observe l'évolution de la fonction cout a travers les itérations.

- Evaluation finale pour évaluer la réelle performance de notre modele avec une métrique populaire (pour votre patron, client, ou vos collegues) on peut utiliser le **coefficient de détermination**,

$\frac{\partial J(\theta) }{\partial \theta} = \frac{1}{m} X^T.(X.\theta - y)$

Ensuite on utilise cette fonction dans la descente de gradient:

$\theta = \theta - \alpha \frac{\partial J(\theta) }{\partial \theta}$

## Chapitre 6: Initiation a l'apprentissage supervisè:


Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#readme-top">Revenir en haut</a>)</p>



### Langages utilisés

Le type fichier que j'utilise dans mes projets est notebook *.ipynb*. Vous pouvez utilisé anaconda en installant tout ce que je vous est mis en bas.
<ul>
    <li> 
    <a href='https://www.python.org/' target="_blank"><img alt='Python' src='https://img.shields.io/badge/Python-100000?style=for-the-badge&logo=Python&logoColor=white&labelColor=214767&color=FDE284'/></a> 
    </li>

  <li>
 <a href='https://docs.anaconda.com/anaconda/install/index.html' target="_blank"><img alt='Anaconda' src='https://img.shields.io/badge/Anaconda-100000?style=for-the-badge&logo=Anaconda&logoColor=white&labelColor=5AAE2C&color=ffffff'/></a>
    </li>
    <li>
    <a href='https://anaconda.org/anaconda/numpy' target="_blank"><img alt='numpy' src='https://img.shields.io/badge/Numpy-100000?style=for-the-badge&logo=numpy&logoColor=4DABCF&labelColor=FFFFFF&color=4D77CF'/></a>
    </li>
    <li>
    <a href='https://anaconda.org/anaconda/pandas' target="_blank"><img alt='pandas' src='https://img.shields.io/badge/pandas-100000?style=for-the-badge&logo=pandas&logoColor=4DABCF&labelColor=FFFFFF&color=151354'/></a>
    </li>
    <li>
    <a href='https://anaconda.org/anaconda/matplotlib' target="_blank"><img alt='matplotlib' src='https://img.shields.io/badge/Matplotlib-100000?style=for-the-badge&logo=matplotlib&logoColor=4DABCF&labelColor=FFFFFF&color=F09568'/></a>
    </li>
    <li>
    <a href='https://anaconda.org/anaconda/scikit-learn' target="_blank"><img alt='seaborn' src='https://img.shields.io/badge/seaborn-100000?style=for-the-badge&logo=seaborn&logoColor=4DABCF&labelColor=FFFFFF&color=F19837'/></a>
    </li>
     
</ul>



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Pour Commencer

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

CHERIF MOHAMED - CherifMohamedAmineUnivFce@gmail.com

Project Link: [https://github.com/mohamed063197/data-Scientist](https://github.com/mohamed063197/data-Scientist)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
