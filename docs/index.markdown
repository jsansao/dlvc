---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Tópicos Especiais: Deep learning aplicado à Visão Computacional (ET094)"
---

**Informações gerais**
-----------------

- Professor Responsável: João Pedro Hallack Sansão
- Carga horária: 72 horas-aula (14 horas-aula síncronas, 58 horas-aulas assíncronas)
- Pré-requisito: Cálculo Numérico 
- [Plano de ensino](/assets/plano_dlcv_20212_ere-4.pdf)


**Introdução**
---------

Neste curso, o aluno terá contato com diversos
problemas de **Aprendizado de Máquina** tratados pela abordagem do
**Aprendizado Profundo** (*Deep Learning*).

O Aprendizado de Máquina é um ramo da **Inteligência Artificial**,
onde o computador extrai as *regras* dos *dados*, sem ser
explicitamente programado. 

O Aprendizado Profundo, por sua vez, é um sub-ramo do
Aprendizado de Máquina. Ele é baseado nas redes neurais
artificiais e a *profundidade* é referência ao número de camadas
intermediárias das redes neurais.


A metodologia do Aprendizado Profundo pode ser empregada em diversas
áreas, como o reconhecimento de fala, processamento natural de
linguagem, séries temporais e em Visão Computacional. 

Para este curso, apresentaremos diversas aplicações da metodologia em
**Visão Computacional** e o aluno poderá acompanhar implementações
práticas do métodos. 



**Algumas aplicações interessantes que serão vistas no curso**
----------

### **Classificação binária** 

Classificar se o animal na imagem é um gato (0) ou cão (1). [^1] 

![Cats vs dogs](/assets/images/catvsdog.png)

### **Classificação com múltiplas classes**

Discriminar entre diversas raças de cães [^2]:

![Competição do Kaggle: Dog Breed Identification](/assets/images/border_collies.png)

Reconhecimento de dígitos: [^3]

![MNIST Digits](/assets/images/digits.jpg)

### **Localização e detecção de objetos** 

Posição e classificação de objetos em uma imagem (ou vídeo, por exemplo) [^4]

![Yolo ](/assets/images/yolo.png)


### **Detecção de faces**

Detecção de face humana [^5]

![SSD](/assets/images/monassd.png)


### **Transferência de estilo e geração**

Adaptar o estilo de uma imagem original, como "Bart Simpson pintado por Picasso". 

Ou mesmo criar uma nova imagem com uma descrição [^6], como "Carro voador pintado por Miró".


<iframe width="560" height="315" src="https://www.youtube.com/embed/FYu2DJ6XuKU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**Recursos computacionais**
----------

Apesar da necessidade de recursos computacionais relevantes para as
aplicações de aprendizado profundo em visão (como GPUs), neste curso
usaremos plataformas de computação em nuvem [^7], que serão suficientes
para o desenvolvimento do mesmo, bastando acesso estável à Internet.


**Maiores informações:**
----------
Entre em contato por e-mail: ![e-mail](/assets/images/email.png)

**Referências**
-----------

[^1]: [Competição no Kaggle: Cats vs Dogs](https://www.kaggle.com/c/dogs-vs-cats)
[^2]: [Competição no Kaggle: Dog breed identification](https://www.kaggle.com/c/dog-breed-identification)
[^3]: [MNIST database](https://en.wikipedia.org/wiki/MNIST_database)
[^4]: [Yolo](https://pjreddie.com/darknet/yolo/)
[^5]: [Detecção de Faces, PyImageSearch](https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/)
[^6]: [VQGAN-CLIP no Huggingface](https://huggingface.co/spaces/akhaliq/VQGAN_CLIP)
[^7]: [Google Colab](https://colab.research.google.com/) e [Kaggle](https://www.kaggle.com)
