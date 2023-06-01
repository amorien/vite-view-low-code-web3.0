# Vite Low-Code Docker App

[Edit on StackBlitz](https://stackblitz.com/edit/vitejs-vite-1ztq8w)

<a href="https://stackblitz.com/edit/vitejs-vite-1ztq8w" target="\_blank">
<img src="https://img.shields.io/badge/Developed%20by%20Adam Morien%20@-URM Stores%20Inc-red">
</a>

# Vite Vue Angular Node.js

<p> A minimalist asynchronous serverless low-code application. </p>

#### Deployed at: https://stackblitz.com/edit/vitejs-vite-1ztq8w

#### Real-time Automation:

<p> You can use this web app to render API's in real-time. Just type in the name of the place in the search bar to experience seamless integration live. </p>

# Features include:

<ul>
  <li> Complete location of the searched place. </li>
  <li> Local time of the place, Date and forecast. </li>
  <li> Autocomplete feature powered by Google Places API. </li>
</ul>

# Docker Instructions

Install [Docker](https://www.docker.com/products/docker-desktop) desktop. After installing it, create an account in Docker and copy the username.

Before running this application in docker, make sure to replace the **API KEYS** placeholder with your own.

```

**Run Docker Container**

You can create your own by following the given steps.

To run the app as a docker container, follow the given steps:

- Navigate to the project directory
  ```bash
  cd atlas-weather-app
  ```
- Replace <strong>USERNAME</strong> with your own username and build the docker image
  ```bash
  docker build -t <USERNAME>/atlas-weather-app:1.0 .
  ```
- Open up the terminal at the project directory, replace <strong>USERNAME</strong> with your own username and run the following command:
  ```bash
  docker run -p 3000:3000 <USERNAME>/atlas-weather-app:1.0
  ```
- You can also use <strong>docker compose</strong> to manage your containers:
  ```bash
  docker-compose up
  ```
  and
  ```bash
  docker-compose down
  ```

# Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**. For more details, check out the [contributing guidelines](CONTRIBUTING.md).

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request.

# License

Distributed under GNU AGPL 3.0. See [LICENSE](LICENSE) for more information.

# Contact

Adam Morien: [https://github.com/amorien.com](https://github.com/amorien.com)

Project Link: [https://github.com/amorien/ViteJS](https://github.com/amorien/ViteJS)
