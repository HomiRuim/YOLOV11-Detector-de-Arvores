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

data: dataset original que foi convertido para o formato COCO para ser devidamente reconhecido pelo YOLOv11 que pode ser encontrado tanto no repositorio https://github.com/pedrozamboni/individual_urban_tree_crown_detection/tree/main como no seguinte link já no drive compactado (github não permite arquivos maiores que 25 megabytes): https://drive.google.com/file/d/1fjvOTsw5FEML8gImZYsJK9tFEb2ulaz8/view?usp=sharing

algumas fotos do resultado do nosso treinamento:

div align="center"
img src="https://github.com/HomiRuim/YOLOV11-Detector-de-Arvores/blob/main/runs/detect/train/train_batch0.jpg" /
/div

div align="center"
img src="https://github.com/HomiRuim/YOLOV11-Detector-de-Arvores/blob/main/runs/detect/train/val_batch0_labels.jpg" /
/div

div align="center"
img src="https://github.com/HomiRuim/YOLOV11-Detector-de-Arvores/blob/main/runs/detect/train/val_batch0_pred.jpg" /
/div
