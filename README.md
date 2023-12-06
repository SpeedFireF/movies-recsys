![Static Badge](https://img.shields.io/badge/LICENSE-MIT-green?link=https%3A%2F%2Fgithub.com%2FSpeedFireF%2Fmovies-recsys)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SpeedFireF/movies-recsys">
    <img src="https://cdn-icons-png.flaticon.com/512/1809/1809826.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Movies recomendation system</h3>

  <p align="center">
    Assignment 2 for PMLDL course
    <br />
    <a href="https://github.com/SpeedFireF/movies-recsys"><strong>Explore the docs »</strong></a>
    <br />
  </p>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#model-architecture">Model Architecture</a></li>
    <li><a href="#contact">Contact</a></li>
     <li><a href="#license">License</a></li>
  </ol>
</details>

## About the project

This project is a movie recommendation system that leverages graph-based techniques to suggest new movies to users based on their tastes and preferences. The system identifies similarities between users and recommends movies liked by similar users.

## Model Architecture

LightGCN, or Light Graph Convolutional Network, is a collaborative filtering recommendation model designed to efficiently capture user-item interactions in recommendation systems. Unlike traditional graph convolutional networks, LightGCN simplifies the convolutional operation by removing the weight parameters associated with user and item nodes. This simplification enhances scalability and reduces computational complexity, making it suitable for large-scale recommendation tasks.

![image](https://github.com/SpeedFireF/movies-recsys/assets/70011787/1911e5e6-b487-4718-9bd6-8eef2f4e76c1)

The core idea behind LightGCN is to propagate user and item embeddings through the user-item interaction graph using a graph convolution operation. The model leverages the inherent structure of the user-item interaction matrix without introducing additional parameters, leading to a more straightforward and computationally efficient approach. By relying on the neighborhood information of users and items, LightGCN effectively captures collaborative signals, enabling accurate recommendations based on user preferences and item characteristics.

<!-- CONTACT -->
## Contact

Abdulayev Damir - [telegram](https://t.me/SpeedFireF) - d.abdulayev@innopolis.university

Project Link: [https://github.com/SpeedFireF/movies-recsys](https://github.com/SpeedFireF/movies-recsys)

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.
