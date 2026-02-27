I was thinking about what to write in my Bio... But I'll let you find out.

Estava pensando no que escrever na minha biografia... Mas vou deixar você descobrir.

npm install pacman-contribution-graph

import { PacmanRenderer } from 'pacman-contribution-graph';

const pr = new PacmanRenderer({
    platform: 'github',
    username: 'yourusername',
    canvas: document.getElementById('canvas'),
    outputFormat: 'canvas',
    gameTheme: 'github'
});
pr.start();
