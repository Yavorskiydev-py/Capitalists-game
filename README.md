# Capitalists game
<img width="1494" alt="Снимок экрана 2025-05-17 в 17 20 13" src="https://github.com/user-attachments/assets/de84e2c2-acfc-46a8-87f3-f5b7e55d4331" />
<img width="1208" alt="Снимок экрана 2025-05-17 в 17 21 10" src="https://github.com/user-attachments/assets/811a988f-f1db-4d78-9e38-feb48f312c76" />
<img width="934" alt="Снимок экрана 2025-05-17 в 17 21 32" src="https://github.com/user-attachments/assets/c0090dd4-cd82-477f-b442-a9c18aafca11" />
<img width="1256" alt="Снимок экрана 2025-05-17 в 17 25 22" src="https://github.com/user-attachments/assets/3d5613aa-1623-4308-9f18-a0b8ef55ffdb" />
<img width="1260" alt="Снимок экрана 2025-05-17 в 17 25 49" src="https://github.com/user-attachments/assets/2943099a-9eff-4219-85a2-d7fb6c42b218" />
<img width="1016" alt="Снимок экрана 2025-05-17 в 17 26 04" src="https://github.com/user-attachments/assets/ce673f75-3ef5-4db2-8e6e-30e9ec9bb011" />
<img width="270" alt="Снимок экрана 2025-05-17 в 17 27 07" src="https://github.com/user-attachments/assets/c060105d-d995-4645-86b8-5c51fd294d4f" />

## Task

Create a game with backend.

## Features

- Live time (using **sockets.io**)
- Pretty designed
- Easy to play
- Has AI enemies (trained using **scikit-learn**)
- Scoreboards
- Can be dockerized

## How to run

```shell
https://github.com/Yavorskiydev-py/Capitalists_game
cd Capitalists_game

# setup virtual environment for backend
cd backend
python -m venv venv
pip install -r requirements.txt

# setup deps for frontend
cd ../frontend
yarn install

# 1 terminal (run backend)
python main.py

# 2 terminal (run game)
yarn dev

# now open http://localhost:3000
```

## Project structure

> backend

Backend by itself, contains train data for AI and game essentials.

> frontend

Frontend written on Nuxt.TS 2.

> [Colab](https://datalore.jetbrains.com/view/notebook/ZFFpCJnDga9pra3ElXTCyG)

Colab for AI model training.

## Credits

- Icons8 for all `*.svg` files
