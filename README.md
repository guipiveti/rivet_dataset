
  

# Inspeção de rebites em latas!
Este projeto tem como propósito comparar dois métodos para inpeção de rebites em latas. Sendo um método clássico e um método baseado em *deep learning* (YOLO 5).
![Rebites](https://raw.githubusercontent.com/guipiveti/rivet_dataset/master/Original/Fraturadas/frat%20(22).bmp)

  
## :scroll: Cartaz
O cartaz do trabalho se encontra disponível através deste [link](https://www.canva.com/design/DAE7zH7mkzE/X6cR8bILtNZWs33wh2-Mpw/view?utm_content=DAE7zH7mkzE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).
## :movie_camera: Apresentação
A apresentação do trabalho se encontra disponível através deste [link](https://youtu.be/s0onHR5sB00).
## :computer: Códigos
### **Abordagem clássica:**

1. [Este arquivo](blob/master/Notebooks/Basic_Rivet_Abordagem_Clássica.ipynb) do Google Colab apresenta para uma única imagem do *dataset* a sequência de procedimentos executados na abordagem clássica a fim de facilitar o entendimento passo a passo dos procedimentos.
2. Baseado no anterior, [este arquivo](https://colab.research.google.com/drive/19hXS9g0q2PQN1uWGPX_z06jMrBgATwZa?usp=sharing) executa a mesma sequência em 80% das imagens do dataset a fim de definir as características esperadas dos rebites não fraturados e assim criar uma árvore de decisão para a classificação. Esta árvore é então aplicada aos 20% restantes avaliando assim sua eficiência.
### **Abordagem por *Deep Learning*:**
1. [Este arquivo](https://colab.research.google.com/drive/1NRD6LyyQs5nOSM0WA2S_kY0RoM7TJ_9u?usp=sharing) do Google Colab contêm a implementação da rede neural YOLO 5 para o *dataset* dos rebites.