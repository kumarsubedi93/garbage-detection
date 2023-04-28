
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">API For Garbage Identifiers With Machine Learning Models  </h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
        <a href="#roadmap"> Road Map </a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Project Home Page

_This project is about identify the garbage with 6 categories ewest, metal, plastic, paper, non-recyclable and glass with Supervise machine learning models_

<br>

### Built With

*  ![Python][Python]
*  ![Fast_API][Fast_API]
*  ![Tensorflow][Tensorflow]


<br>
<!-- GETTING STARTED -->
## Getting Started

Here are the instructions about settings up project in local environment

### Prerequisites

* Python3.10


### Installation


1. Clone the repo
   ```sh
   git clone git@github.com:kumarsubedi93/garbage-detection.git
   ```
2. Create python virtual environment
   ```sh
    python3 -m venv env
   ```
3. Activate virtual environment
   ```sh
   source env/bin/activate
   ```
4. Install all require packages

   ```sh
    pip install -r requirements.txt
   ```

5. Get Machine learning models by following link and place inside *ml-models/*
    ```
    https://www.dropbox.com/s/jxlv29rh8otxrtx/garbage_model_weights.h5?dl=0
    ```
6.  Run project by using below command
    ```
     python main.py  
    ```

7. The project up and running  in localhost:900 port & got to localhost:9000/docs to get API Endpoint.
<br>


<!-- ROADMAP -->
## Roadmap

- [x] Add More data on training models




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




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


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


[product-screenshot]: rlfoods/website/static/img/project-homepage.png
[Django_url]:https://www.djangoproject.com/
[Django]:https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white
[MYSQL_url]:https://www.mysql.com/
[MYSQL]:https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white
[Bootstrap]:https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap_url]:https://getbootstrap.com

[Python]:https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat
[Fast_API]:https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=fff&style=flat
[Tensorflow]:https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=fff&style=flat
