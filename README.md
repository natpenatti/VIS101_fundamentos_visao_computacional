# 👁️ Fundamentos da Visão Computacional

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.x-lightblue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange.svg)
![Ultralytics](https://img.shields.io/badge/Ultralytics-YOLOv11-black.svg)
![Supervision](https://img.shields.io/badge/Supervision-Roboflow-purple.svg)
![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow)

Repositório dedicado aos códigos, exercícios e anotações da disciplina de **Fundamentos da Visão Computacional** da Pós em Visão Computacional e Deep Learning no STAR Research Institute. O foco principal é compreender a cadeia de formação da imagem digital e aplicar operações de leitura, inspeção e manipulação utilizando OpenCV, estabelecendo a base para o aprendizado de máquina aplicado à visão moderna.

## 📖 Sobre a Disciplina

**Instrutor:** Carlos Melo, MSc.

**Ementa:**
Natureza e desafios da visão computacional. Um sistema de visão simples: pipeline completo de análise em um mundo visual simplificado. Percepção visual e leitura de imagens: intensidade, contraste e histograma. Formação da imagem: luz e espectro eletromagnético, energia do fóton, modelo pinhole, lentes e câmera como sistema linear. Sensores de imagem, amostragem e quantização. Cor: espaços de cor e mosaico de Bayer. O paradigma de aprendizado na visão computacional moderna. Introdução ao OpenCV.

**Bibliografia Base:**
* TORRALBA, A.; ISOLA, P.; FREEMAN, W. T. Foundations of Computer Vision. Cambridge: MIT Press, 2024. (caps. 1–11; disponível em visionbook.mit.edu)

## 🎯 Objetivos

**Objetivo Geral:**
Desenvolver competências para compreender a formação da imagem digital — da radiação eletromagnética ao pixel — e o paradigma de aprendizado que fundamenta a visão computacional moderna, estabelecendo a base conceitual das disciplinas subsequentes do programa.

**Objetivos Específicos:**
* **Identificar** os elementos da cadeia de formação da imagem (espectro eletromagnético, óptica, sensor, amostragem, quantização) e seus efeitos sobre a imagem digital.
* **Descrever** o desafio da visão computacional e os componentes de um sistema de visão completo.
* **Aplicar** operações de leitura, inspeção e manipulação básica de imagens com OpenCV.
* **Relacionar** o aprendizado de máquina à visão computacional como paradigma central da área.

## 📂 Estrutura do Repositório

O projeto está estruturado em diretórios para separar scripts, dados brutos e modelos de Inteligência Artificial:

* `images/`
  * `apple.jpg`
  * `brasil-moedas.jpg`
  * `cat.jpeg`
  * `dog.png`
  * `rua.webp`
* `models/`
  * `yolo26n.pt`
* `notebooks/`
  * `VIS101_aula2_segmentacao_maca.ipynb`
  * `VIS101_aula2_transformacoes_geometricas.ipynb`
  * `VIS101_aula3_intensidade_e_histograma.ipynb`
  * `VIS101_aula4_do_histograma_ao_threshold.ipynb`
  * `VIS101_aula4_anotacoes_em_imagens.ipynb`
  * `VIS101_aula4_anotacoes_com_supervision.ipynb`
  * `VIS101_aula5_espacos_de_cor.ipynb`
  * `VIS101_aula5_segmentacao_por_cor_hsv.ipynb`
  * `VIS101_aula5_chroma_key_video.ipynb`
* `videos/`
  * `chuva-bolas-3cores.mp4`
  * `fundo-deserto.mp4`
  * `greenscreen.mp4`
  * `people-walking.mp4`

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/natpenatti/VIS101_fundamentos_visao_computacional.git](https://github.com/natpenatti/VIS101_fundamentos_visao_computacional.git)
   cd VIS101_fundamentos_visao_computacional