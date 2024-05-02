# Chess-Vision-Connect

## Introduction

During my journey in deep learning, I've been searching for a project that not only enhances my skills but also let me feel motivated to work on. That's when the idea of Chess-Vision-Connect emerged.

## How Does It Work?

![Chess-Vision-Connect Output](https://github.com/mouadenna/Chess-Vision-Connect/blob/main/output.png?raw=true "Chess-Vision-Connect Output")

First, I uploaded the YOLO models I used, which are YOLOv8s for chess piece detection and YOLOv8n for detecting corners. I made a concerted effort to balance performance and speed, ensuring these models are among the best available. You can access these models on Kaggle from this [link](https://www.kaggle.com/datasets/mouadenna/models-chessvision). Additionally, I utilized the Stockfish engine to evaluate chess positions. You can download it from the official website (here)[https://stockfishchess.org/download/]. However, please note that you should not run the notebook on a cloud environment, as I have already tried and my kaggle account got banned due to the Stockfish executable file.


Furthermore, if you happen to have the same chess board as mine, it would be great.

The main pipeline of the project involves processing a chessboard image to extract game state details. It begins by resizing and aligning the image properly. Then, it detects chess pieces, transforms their positions, and generates a board state representation, as a FEN format. it infers a move and highlights it on the board.

The entire process is shown in the figure below:

![Full Process](https://github.com/mouadenna/Chess-Vision-Connect/blob/main/full%20process.png)

## Project Duration

This project has been a significant investment of my time, taking about two months to complete. Although it presented its challenges, the experience I gained was incredibly valuable, helping me to delve deeper into the vast realms of deep learning, computer vision, and the fascinating game of chess.
