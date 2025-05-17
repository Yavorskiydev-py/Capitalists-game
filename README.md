# Capitalists game
<img width="1249" alt="Снимок экрана 2025-05-17 в 17 46 12" src="https://github.com/user-attachments/assets/cec8d4c1-0c20-45cc-a2ef-24d24c2bfddf" />
<img width="1721" alt="Снимок экрана 2025-05-17 в 17 47 03" src="https://github.com/user-attachments/assets/48ad5f8f-e80b-48d0-8075-27329764bd59" />
<img width="916" alt="Снимок экрана 2025-05-17 в 17 48 23" src="https://github.com/user-attachments/assets/972bcc8b-91a5-427f-b3a9-e1f4e86f3bb3" />
<img width="1599" alt="Снимок экрана 2025-05-17 в 17 47 15" src="https://github.com/user-attachments/assets/eeebe11a-a51c-4926-894a-037cf357983a" />
<img width="478" alt="Снимок экрана 2025-05-17 в 17 47 51" src="https://github.com/user-attachments/assets/8e8c36cc-7fa1-49f0-8df5-0c4e0ff9c95f" />


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
