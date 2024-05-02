# Chess-Vision-Connect

## Introduction

Throughout my journey in deep learning, I've been on the lookout for a project that not only enhances my skills but also brings me joy. That's when the idea of Chess-Vision-Connect emerged. 

## How Does It Work?

![Chess-Vision-Connect Output](https://github.com/mouadenna/Chess-Vision-Connect/blob/main/output.png?raw=true "Chess-Vision-Connect Output")


At the heart of Chess-Vision-Connect are YOLOv8 models meticulously trained on my personal chess board. Striking a balance between performance and speed was paramount, leading me to deploy YOLOv8s for chess piece detection and YOLOv8n for corner detection. You can access these models on Kaggle [here](https://www.kaggle.com/datasets/mouadenna/models-chessvision).

Additionally, to evaluate chess positions, I integrated the renowned Stockfish engine. However, I must caution against running the notebook on a cloud environment, as my account was previously banned due to the Stockfish executable file.

Furthermore, if you happen to possess the same chess board as mine, it would be great.

The main pipeline of the project involves processing a chessboard image to extract game state details. It begins by resizing and aligning the image properly. Then, it detects chess pieces, transforms their positions, and generates a board state representation, often in FEN format. If required, it infers a move and highlights it on the board. 




## Project Duration

This project has been a labor of love, consuming approximately two months of my time. Despite the challenges, the experience gained has been invaluable, deepening my understanding of both deep learning and the intricacies of chess.
