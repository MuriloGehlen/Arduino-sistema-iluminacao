1)
Entradas:
- luz identificada pelo fotorresistor
- um botão para o LED atender ao LDR
- um botão para manter permanentemente o estado de alerta
- um botão para desligar o sistema
Saídas:
LED RGB de cores verde, amarelo e vermelho

2) Componentes:
- Arduino para a programação dos outros componentes
- Placa de ensaio para interligar todas as outras peças
- Fotorresistor para medir a quantidade de luz no ambiente
- LED RGB para uma resposta visual sobre o quão escuro ou claro está o ambiente
- Resistores para controlar a corrente elétrica e não alterar de forma errônea as cores do LED RGB
- Botões para desligar o sistema, manter o estado de alerta e voltar para a atividade normal do LDR e do LED RGB

3) Regras de funcionamento:
- O led deve ligar uma cor referente à iluminação do ambiente
- Verde refere ao ambiente claro
- Amarelo se refere ao ambiente com iluminação média
- Vermelho se refere ao ambiente escuro
- um botão deve manter permanentemente vermelho no LED
- um botão deve fazer o LED ser referente ao LDR novamente
- um botão deve desligar todo o sistema
- se dois botões forem apertados, não deve ter mudança no sistema.

4) eu utilizaria IF para controlar primeiramente um uma variável que guardaria um valor que seria referente ao estado do sistema. Cada botão, quando apertado, mudaria o valor dessa variável mudando, consequentemente, o estado do sistema. No primeiro estado, teria 3 IFs, um para cada cor do RGB referente ao valor retirado do LDR. Após isso, colocaria um IF para mudar para o estado de alerta permanente, e em seguida um IF para mudar para o estado de desligado.


<img width="1186" height="703" alt="image" src="https://github.com/user-attachments/assets/743f5219-c92b-4304-8f81-41c4434a7af2" />
<img width="396" height="789" alt="image" src="https://github.com/user-attachments/assets/15aa536c-0b40-4626-82af-064c3deb634a" />
<img width="190" height="168" alt="image" src="https://github.com/user-attachments/assets/d5e58b32-5028-497e-8847-faef5b646c03" />
