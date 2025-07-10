# YOLOV11-Detector-de-Arvores

Trabalho feito para a disciplina de Introdução à Inteligência Artificial na Universidade de Brasília com o professor Dr. Dibio Leandro Borges

Autores:
Davi de Araújo Garcez Bueno - 211060586

Célio Júnio de Freitas Eduardo - 211010350

Ana Luiza Campos Souza - 211055441

Nesse trabalho, utilizamos o YOLO v11 em um dataset customizado de imagens de satélite contendo árvores, e treinamos o mesmo para identificar corretamente as árvores
nas imagens.

Arquivo ipynb: notebook jupyter executado no ambiente Google Colab configurado com a GPU T4

runs/detect/train: arquivos resultantes da execução do ipynb, com métricas e gráficos, além das fotos do resultado do treinamento e validação do modelo no dataset customizado

data: dataset original que foi convertido para o formato COCO para ser devidamente reconhecido pelo YOLOv11 que pode ser encontrado tanto no repositorio 

https://github.com/pedrozamboni/individual_urban_tree_crown_detection/tree/main 

como no seguinte link já no drive compactado (github não permite arquivos maiores que 25 megabytes): https://drive.google.com/file/d/1fjvOTsw5FEML8gImZYsJK9tFEb2ulaz8/view?usp=sharing

algumas fotos do resultado do nosso treinamento:

Imagem 1:
![train_batch0](https://github.com/user-attachments/assets/5f69ac57-6fc6-4d1d-9f85-b8916f507809)

Imagem 2:
![val_batch0_labels](https://github.com/user-attachments/assets/df020073-dcb6-440d-aa50-ebe9a362b7d2)

Imagem 3:
![val_batch0_pred](https://github.com/user-attachments/assets/84f598ae-f1d2-47c6-9297-f849c8d3e137)

