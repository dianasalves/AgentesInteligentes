# Agentes Inteligentes

  O(s) agentes(s) corta-relvas são reativos (sem memória) possuem um objetivo: cortar células com relva. Cada agente consegue percecionar se a célula imediatamente em frente, 
à sua direita e à sua esquerda têm a relva cortada ou não. Mediante as perceções cada agente pode executar as ações de movimento em frente, rotação para a sua direita (90º) e
rotação para a sua esquerda (-90º). A versão disponibilizada caracteriza-se pelo seguinte pelo 
seguinte comportamento:
    • enquanto encontrar quadrados a verde o corta-relvas segue sempre em frente numa direção inicializada aleatoriamente no conjunto: [0º,90º,180º,270º];
    • quando encontrar um quadrado com a relva já cortada (castanho) em frente com relva para cortar à sua direita faz uma rotação de 90º;
    • quando encontrar um quadrado com a relva já cortada (castanho) em frente com relva para cortar à sua esquerda faz uma rotação de -90º;
    • caso nenhuma das condições anteriores se verifique o corta-relvas segue em frente;
    • o corte de um quadrado de relva implica a mudança da cor de verde para castanho.
    • na interface contém um monitor para visualizar o número total de movimentos efetuados pelo agente. 
    • 3 corta-relvas operem simultaneamente. 
    • Existem dois tipos de agentes: os corta-relvas e as pragas. Hipoteticamente, existe um tipo de praga no relvado que faz com que a relva cresça de uma forma super-rápida 
num local aleatório. Sempre que a praga avançar um quadrado a relva é reposta. A praga efetua ações de rotação aleatórias de 90º e -90º segundo uma probabilidade a definir.
