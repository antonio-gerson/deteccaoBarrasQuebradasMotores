# Detecção por Inteligência Artificial de Barras Quebradas em Rotores de Motores de Indução Trifásicos.
    
       
  A coleta de dados dos equipamentos é uma atividade rotineira dos atores da Manutenção Preditiva, sendo que os dados formam a matéria-prima quando se trata de Data Science. A junção dessas ferramentas possibilita desenvolver métodos preditivos contribuindo para a evolução da
Indústria.

  Este trabalho foi desenvolvido com o objetivo de detectar a falha acerca das barras quebradas em motores elétricos, utilizando-se de dados disponibilizados através do experimento para detecção e disgnóstico de barras quebradas em rotores de motor de indução trifásico desenvolvido no Laboratório de Automação Inteligente de Processos e Sistemas e no Laboratório de Controle Inteligente de Máquinas Elétricas da Escola de Engenharia de São Carlos da Universidade de São Paulo (USP),
Brasil.

  O experimento fonte dos dados consistiu em um protótipo montado sobre uma bancada, em diversas condições operacionais, sendo monitorado constantemente por sensores posicionados estrategicamente de modo a medir as unidades de tensão e corrente elétrica, além de vibrações mecânicas.
      O motor em questão foi submetido a cinco tipos de condicionamento, sendo eles: Motor Normal (sem barra quebrada), Motor com 1, 2, 3 e 4 barras quebradas em condições de torque 5, 10,15, 20, 25, 30, 35 e 40 Nm. Os sensores forneceram os dados que serviram de base para este trabalho.
    
  Para o desenvolvimento do trabalho foi necessário aprofundar os conhecimentos em uma das técnicas matemáticas mais utilizadas quando se trata da transformação de sinais elétricos, a Fast Fourier Transform (FFT) sendo que esta técnica fundamental no processo de transformação dos dados para este trabalho.
  
  Dentre as ferramentas utilizadas neste trabalho, destacam-se a linguagem de programação Python e as bibliotecas Pandas, Numpy, Scikit Learn e Tensor Flow. A biblioteca mat73 foi necessária pois os dados do experimento utilizado se encontravam em formato .mat (matlab) e o intuito era se trabalhar a partir de arquivos do tipo csv. Para a etapa de Feature Enginnering utilizou-se as técnicas de FFT e Principal Component Analysis (PCA) e a modelagem com Redes Neurais
Artificiais.
