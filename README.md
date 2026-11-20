# Jogo_Arquitetura_Computacional

# Jogos de Arquitetura Computacional

Projeto desenvolvido para a atividade avaliativa da **Sprint 3** da disciplina de **Arquitetura Computacional**. A aplicação reúne três modos interativos no navegador para revisar conceitos de hardware e arquitetura de computadores: **Cruzadinha**, **Flashcards** e **Caça-Palavras**, com visual temático em **amarelo e azul**, barra de progresso com carrinho e navegação entre os modos pelo topo.

---

## Modos de Jogo e Como Jogar

### 1. Cruzadinha (`index.html`)
1. **Leia as pistas:** Consulte as pistas separadas entre **Horizontais** e **Verticais**.
2. **Preencha o tabuleiro:** Digite as letras diretamente nas casas do grid (sem acentos e sem espaços).
3. **Confira o progresso:** Clique em **Conferir** para validar as respostas e acompanhar seu desempenho.
4. **Reinicie quando quiser:** Use **Reiniciar** para limpar o tabuleiro e tentar novamente.

### 2. Flashcards (`flashcard.html`)
1. **Leia a pergunta:** Cada cartão apresenta um conceito essencial de hardware e arquitetura computacional.
2. **Vire o cartão:** Clique no cartão, no botão **Virar cartão** ou use **Espaço** / **Enter** no teclado para ver a resposta.
3. **Navegue entre os cards:** Use os botões **Anterior** / **Próximo** ou as setas **←** e **→** do teclado enquanto acompanha o progresso na pista.

### 3. Caça-Palavras (`caca-palavra.html`)
1. **Leia as dicas:** Em vez da palavra pronta, o painel lateral exibe dicas para você descobrir qual termo procurar no tabuleiro `14x14`.
2. **Selecione as letras:** Clique letra por letra (da primeira à última; também funciona de trás para frente) ou use **Limpar seleção** para desfazer cliques.
3. **Revelação e nova rodada:** Ao encontrar uma palavra, a dica correspondente é marcada como concluída e exibe o termo encontrado. Ao completar todas as **13 palavras**, o tabuleiro gera uma nova disposição de letras automaticamente.

---

## Conteúdo da Cruzadinha

### Horizontais
1. **MICROCONTROLADOR:** Chip único que integra processador, memória e periféricos para sistemas embarcados.
4. **ADDRESSBUS:** Via unidirecional que indica a localização exata na memória para leitura ou escrita.
6. **REGISTRADORES:** Unidades internas de armazenamento mais velozes situadas dentro do processador.
8. **DATABUS:** Canal bidirecional por onde trafegam informações entre componentes e processador.
10. **FLASH:** Memória não volátil de escrita rápida usada em SSDs e pendrives.
11. **CACHE:** Memória intermediária ultrarrápida que guarda cópias de dados mais acessados.

### Verticais
2. **CPU:** Cérebro do computador que interpreta e executa as instruções dos programas.
3. **RAM:** Memória principal volátil usada para guardar programas abertos temporariamente.
5. **DUALCORE:** Processador que integra dois núcleos independentes de execução no mesmo chip.
7. **ROM:** Memória apenas de leitura que guarda instruções permanentes de inicialização.
9. **DMA:** Recurso que permite periféricos acessarem a memória sem sobrecarregar a CPU.
12. **ULA:** Parte do processador que executa cálculos matemáticos e operações lógicas.

---

## Conteúdo dos Flashcards (8 Cartões)
- **Função principal da CPU:** Buscar, decodificar e executar instruções de programas.
- **ULA:** Execução de cálculos aritméticos e operações lógicas de comparação.
- **Unidade de Controle (UC):** Gerenciamento do fluxo de dados e coordenação interna do processador.
- **Registradores:** Memórias internas ultrarrápidas localizadas dentro da CPU.
- **RAM vs. ROM:** Diferença entre memória volátil (dados temporários em execução) e não volátil (instruções permanentes).
- **DMA:** Transferência direta de dados entre periféricos e memória sem sobrecarregar a CPU.
- **Address Bus vs. Data Bus:** Transporte de endereços de memória versus transporte de dados lidos ou gravados.
- **Microcontrolador:** Circuito integrado único com CPU, memória e periféricos para sistemas embarcados.

---

## Palavras do Caça-Palavras (13 Termos com Dicas)
- **CPU**
- **ULA**
- **CACHE**
- **FLASH**
- **RAM**
- **ROM**
- **DUALCORE**
- **QUADCORE**
- **DMA**
- **BARRAMENTO**
- **BIOS**
- **CLOCK**
- **SSD**


- **GitHub Pages:** Publique o repositório e acesse em `https://SEU-USUARIO.github.io/Jogo_Arquitetura_Computacional/` *(substitua `SEU-USUARIO` pelo seu usuário do GitHub)*.