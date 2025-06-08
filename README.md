# Bluum-rasp

## Project Description
Bluum-rasp is a simple scaffold for a 3D web application. The project combines a Vite front-end that uses Three.js for rendering with an Express.js back-end server. It is intended as a starting point for interactive visualizations that can run on lightweight devices such as the Raspberry Pi.

## Description du projet
Bluum-rasp est un squelette de projet pour une application web 3D. Il associe un front-end Vite utilisant Three.js pour l'affichage et un serveur Express.js pour l'API. Ce dépôt sert de base pour créer des visualisations interactives capables de fonctionner sur des appareils légers comme le Raspberry Pi.

## Running Locally
1. Install [Node.js](https://nodejs.org/).
2. Clone this repository and navigate into it:
   ```bash
   git clone <repository-url>
   cd bluum-rasp
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the Express server:
   ```bash
   npm run server
   ```
5. In another terminal, start the Vite development server:
   ```bash
   npm run dev
   ```
6. Open your browser to the provided local address to view the Three.js scene.

## Contributing
Contributions are welcome! Please fork the repository and open a pull request with your proposed changes. Be sure to include a clear description of your additions and follow established code conventions.

## License
This project is licensed under the [MIT License](LICENSE).
