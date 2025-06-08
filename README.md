# Bluum-rasp

## Concept

Bluum est un life-sim contemplatif : un diorama 3D isométrique rétro où des formes de vie abstraites poussent, mutent et se sélectionnent en continu, même lorsque personne ne regarde. Le joueur agit en simple observateur ; toute la magie vient d’une simulation génétique et énergétique qui s’auto-régule pour offrir un spectacle organique hypnotisant.

### Pourquoi c’est excitant

| Atout | Impact |
| ----- | ------ |
| Émergence visuelle | la vie change vraiment à chaque partie, attache émotionnelle immédiate |
| Persistance serveur | le monde continue d’évoluer 24 h/24 sur un Raspberry Pi |
| Esthétique rétro-low-poly | look PS1 / voxel avec HUD pixel-art ✔️ |
| Architecture modulaire | front Three.js ↔ back Node/WebSocket ; facile à étendre (multi-mondes, events, etc.) |

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

This project uses [Jest](https://jestjs.io/) for unit testing.

## Setup

Install dependencies:

```bash
npm install
```

Run tests:

```bash
npm test
```


## Contributing
Contributions are welcome! Please fork the repository and open a pull request with your proposed changes. Be sure to include a clear description of your additions and follow established code conventions.

## License

This project is licensed under the [MIT License](LICENSE).
