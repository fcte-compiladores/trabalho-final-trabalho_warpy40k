# WarPy40K

A Warhammer 40K-themed toy programming language and interpreter, designed for fun, learning, and extensibility. WarPy40K features a custom syntax, unique commands, and robust tooling including a linter and syntax highlighting extensions for VS Code and Sublime Text.

## Sobre o Universo Warhammer 40K

### O Que é Warhammer 40,000?

Warhammer 40,000 (também conhecido como Warhammer 40K ou WH40K) é um universo de ficção científica criado pela Games Workshop em 1987. Ambientado no ano 40,000 (daí o nome), é um futuro sombrio onde "há apenas guerra" (*"In the grim darkness of the far future, there is only war"*).

### O Universo

O universo de Warhammer 40K é caracterizado por:

- **Imperium of Man**: Um império galáctico totalitário liderado pelo God-Emperor of Mankind, que governa milhões de mundos através de uma burocracia massiva e opressiva
- **Space Marines**: Guerreiros geneticamente modificados, os Adeptus Astartes, conhecidos como "Angels of Death"
- **Chaos**: Forças demoníacas da Warp (uma dimensão paralela) que corrompem e destroem
- **Xenos**: Raças alienígenas como Orks (criaturas brutais obcecadas com guerra), Eldar (antiga raça psíquica), Tyranids (enxame devorador), entre outros
- **Technological Decay**: A humanidade perdeu muito conhecimento tecnológico, tratando máquinas como objetos religiosos
- **Grimdark**: O universo é intencionalmente sombrio, onde não há "mocinhos" verdadeiros e a sobrevivência é uma luta constante

### O Jogo de Tabuleiro

Warhammer 40,000 é um jogo de estratégia em miniatura onde:

1. **Exércitos**: Cada jogador monta um exército escolhendo entre diferentes facções (Space Marines, Orks, Chaos, Eldar, etc.)
2. **Miniaturas**: Jogadores compram, montam e pintam miniaturas detalhadas representando soldados, veículos e criaturas
3. **Regras**: Sistema complexo de regras para movimento, combate, habilidades especiais e magia (poderes psíquicos)
4. **Dados**: Usa principalmente dados de 6 faces (d6) para determinar acertos, ferimentos e saves
5. **Turnos**: Jogadores alternam turnos movendo suas unidades, atirando e combatendo corpo-a-corpo
6. **Objetivos**: Vitória através de eliminação do inimigo ou controle de objetivos no tabuleiro
7. **Customização**: Listas de exército altamente customizáveis com diferentes unidades, equipamentos e estratégias

### Elementos Temáticos no WarPy40K

Nossa linguagem de programação incorpora elementos autênticos do universo Warhammer 40K:

#### Tipos de Dados Temáticos
- **`dg`** (Digit): Números, representando dados e cálculos táticos
- **`servitor`**: Referência aos servitors (humanos lobotomizados que operam máquinas)
- **`blob`**: Inspirado nas "blob squads" (grandes grupos de guardsmen imperiais)
- **`psykers`**: Referência aos psykers (humanos com poderes psíquicos)
- **`void_shields`**: Sistema de proteção de naves espaciais imperiais

#### Comandos Inspirados no Lore
- **`the_emperor_protects`**: Frase icônica de proteção imperial
- **`burn_the_heretic`**: Usado para output/print, referenciando a purificação de hereges
- **`vox_cast`**: Sistema de comunicação imperial para input/output
- **`WAAAGH`**: Grito de guerra dos Orks
- **`blood_for_the_blood_god`**: Invocação do Chaos God Khorne
- **`for_the_emperor`**: Grito de batalha dos Space Marines

### Objetivo do WarPy40K

O projeto WarPy40K tem múltiplos objetivos educacionais e recreativos:

#### Objetivos Educacionais
1. **Aprendizado de Compiladores**: Demonstrar conceitos de análise léxica, sintática e semântica
2. **Design de Linguagens**: Explorar como criar uma linguagem de programação com identidade própria
3. **Análise Estática**: Implementar um linter funcional para detecção de erros
4. **Tooling**: Desenvolver ferramentas auxiliares como syntax highlighting

#### Objetivos Recreativos
1. **Imersão Temática**: Permitir que fãs de Warhammer 40K programem usando vocabulário familiar
2. **Comunidade**: Criar uma ponte entre comunidades de programação e gaming
3. **Criatividade**: Inspirar projetos únicos que combinem hobbies diferentes

#### Objetivos Técnicos
1. **Funcionalidade Completa**: Suportar estruturas de controle, variáveis tipadas e operações aritméticas
2. **Extensibilidade**: Arquitetura que permite fácil adição de novos comandos e tipos
3. **Qualidade**: Código limpo, bem documentado e testado
4. **Acessibilidade**: Ferramentas que facilitam o uso (linter, syntax highlighting, exemplos)

### Por Que Warhammer 40K?

Por que foi escolhido o universo Warhammer 40K?

1. **Vocabulário Rico**: O universo possui terminologia técnica extensa que se adapta bem a conceitos de programação
2. **Comunidade Apaixonada**: Fãs de 40K apreciam referências autênticas e detalhadas ao lore
3. **Estética Distintiva**: A estética "grimdark" cria uma identidade visual e conceitual única
4. **Complexidade**: O universo é complexo o suficiente para inspirar funcionalidades avançadas
5. **Nostalgia e Diversão**: Combina o aprendizado técnico com elementos lúdicos familiares

O WarPy40K não é apenas uma linguagem de programação - é uma homenagem a um universo rico e uma ferramenta educacional que torna o aprendizado de compiladores mais envolvente e memorável.

*"Knowledge is power, guard it well."* - Adeptus Mechanicus

## Funcionalidades

- **Linguagem Customizada**: Sintaxe e comandos inspirados no Warhammer 40K
- **Operações Aritméticas**: Suporte completo para adição (+), subtração (-), multiplicação (*), divisão (/) e módulo (%) com precedência adequada de operadores
- **Controle de Fluxo**: Condicionais if-else, loops for e loops while
- **Variáveis**: Declarações de variáveis tipadas e atribuições
- **Interpretador**: Execute scripts `.wp40k` diretamente com Python
- **Linter**: Análise estática abrangente para sintaxe, variáveis e estilo ([veja documentação do linter](./docs/LINTER_README.md))
- **Destaque de Sintaxe**: Extensões oficiais para VS Code e Sublime Text
- **Arquivos de Teste**: Scripts de exemplo para aprendizado e validação

## Casos de Uso e Aplicações

A linguagem WarPy40K pode ser utilizada em diversos contextos educacionais, recreativos e práticos:

### 📚 Educação e Aprendizado

**Ensino de Compiladores**
- Demonstrar conceitos de parsing, AST e interpretação de forma prática
- Exemplificar design de linguagens de programação com identidade temática
- Ensinar análise estática através do linter integrado
- Mostrar implementação de extensões de editor (VS Code/Sublime Text)

**Workshops e Palestras**
- Material didático para conferências de programação
- Demonstrações interativas sobre criação de DSLs (Domain-Specific Languages)
- Exemplos práticos de como combinar hobbies com programação

### 🎮 Entretenimento e Comunidade

**Gamificação do Aprendizado**
- Tornar o estudo de compiladores mais envolvente para fãs de Warhammer 40K
- Criar desafios de programação com temática do universo grimdark
- Desenvolver mini-jogos ou simulações usando a sintaxe temática

**Projetos da Comunidade**
- Scripts para calcular estatísticas de batalha do jogo de tabuleiro
- Simuladores de combate simples
- Geradores de lore e narrativas temáticas
- Calculadoras de pontos de exército

### 🔧 Aplicações Práticas

**Prototipagem Rápida**
- Testar conceitos de algoritmos com sintaxe única e memorável
- Criar protótipos de sistemas de regras para jogos
- Desenvolver ferramentas auxiliares para hobbies relacionados

**Automação Temática**
```warpy40k
# Exemplo: Calculadora de dano de armas
weapon_strength: dg = 8
target_toughness: dg = 4
armor_save: dg = 3

# Calcular chance de ferimento
wound_roll: dg = 7 - weapon_strength + target_toughness
if wound_roll <= 2:
    wound_roll = 2

burn_the_heretic("Ferimento em: " + str(wound_roll) + "+")
```

### 🎯 Casos de Uso Específicos

**1. Simulação de Batalhas Simples**
- Implementar sistemas de combate básicos
- Calcular probabilidades de acerto e ferimento
- Simular sequências de ataques e defesas

**2. Geração de Conteúdo**
- Scripts para gerar nomes de personagens imperiais
- Criação automática de missões e cenários
- Geração de estatísticas de unidades

**3. Ferramentas de Apoio ao Jogo**
- Calculadoras de pontos de exército
- Verificadores de regras básicas
- Contadores de recursos e turnos

**4. Ensino de Lógica de Programação**
- Introdução a conceitos básicos com vocabulário familiar
- Exercícios de algoritmos em contexto temático
- Projetos de programação criativa

### 🚀 Expansibilidade

**Extensões Futuras Possíveis**
- Integração com APIs de dados do Warhammer 40K
- Exportação para outras linguagens (transpilação)
- Interface gráfica temática para desenvolvimento
- Plugins para ferramentas de desenvolvimento de jogos

**Comunidade e Contribuições**
- Base para desenvolvedores criarem suas próprias extensões temáticas
- Framework para outras linguagens inspiradas em universos ficcionais
- Modelo para projetos educacionais criativos

O WarPy40K serve tanto como ferramenta educacional séria quanto como projeto divertido que une programação e cultura geek, demonstrando que o aprendizado técnico pode ser envolvente e memorável.

## Instalação

1. Instale as dependências:
   ```bash
   pip install lark-parser
   ```

2. Clone o repositório:
   ```bash
   git clone https://github.com/fcte-compiladores/trabalho-final-trabalho_warpy40k.git
   cd trabalho-final-trabalho_warpy40k
   ```

## Integrantes

- Nome: Davi Casseb - Matrícula: 211031682 - Turma: 18h
- Nome: Nathan Abreu - Matrícula: 221022696 - Turma: 18h

## Uso

Para rodar um script WarPy40K:
```bash
python3 warpy_interpreter.py tests/test_simple.wp40k
```

Para rodar o lint num script:
```bash
python3 warpy_linter.py tests/test_simple.wp40k
```

## Exemplo

```warpy40k
# Operações aritméticas básicas
a: dg = 10
b: dg = 3
c: dg = 2

# Adição e subtração
result1: dg = a + b      # 13
result2: dg = a - b      # 7

# Multiplicação e divisão
result3: dg = a * b      # 30
result4: dg = a / b      # 3.333...

# Operação de módulo
result5: dg = a % b      # 1

# Expressões complexas com precedência
complex: dg = a + b * c  # 16 (não 26 devido à precedência)

# Parênteses para alterar precedência
paren: dg = (a + b) * c  # 26

# Sequência de Fibonacci com aritmética
start: dg = 0
end: dg = 5

a: dg = 0
b: dg = 1
i: dg = 0
c: dg = 0

if start == 0:
    burn_the_heretic(a)

for i in 1..end:
    c = a + b
    a = b
    b = c
    if i >= start and i <= end:
        burn_the_heretic(a)
```

## Ferramentas

- **Linter**: Veja [LINTER_README.md](./docs/LINTER_README.md) para códigos de erro, integração e uso avançado.
- **Highlighter**:
  - VS Code: Veja `warpy40k-syntax/README.md`
  - Sublime Text: Veja `warpy40k-sublime/README.md`

## Referências

Este projeto foi desenvolvido utilizando as seguintes referências e tecnologias:

- **Lark Parser**: Biblioteca Python para parsing e análise sintática. Utilizada como base para implementar a análise léxica e sintática da linguagem WarPy40K. Site oficial: [https://github.com/lark-parser/lark](https://github.com/lark-parser/lark)
- **Warhammer 40K Universe**: Inspiração temática para nomes de comandos, tipos de dados e estética geral da linguagem. Propriedade da Games Workshop.
- **Crafting Interpreters**: Conceitos fundamentais de design de linguagens de programação e implementação de interpretadores, especialmente para estruturas de AST e avaliação de expressões.
- **Python Official Documentation**: Referência para implementação do interpretador e estruturas de dados.

### Contribuições Originais

- **Gramática WarPy40K**: Sintaxe completamente original inspirada no universo Warhammer 40K
- **Sistema de Tipos Temáticos**: Tipos de dados únicos (`dg`, `servitor`, `blob`, `psykers`, `void_shields`)
- **Comandos Temáticos**: Set completo de comandos inspirados no lore do Warhammer 40K
- **Linter Integrado**: Sistema de análise estática customizado para a linguagem
- **Extensões de Syntax Highlighting**: Plugins originais para VS Code e Sublime Text

## Estrutura do Código

O projeto está organizado nos seguintes módulos principais:

### Arquivos Principais

- **`warpy_interpreter.py`**: Contém o interpretador principal e todas as etapas de compilação
  - **Análise Léxica**: Definida na gramática Lark (linhas 6-65) com tokens, palavras-chave e operadores
  - **Análise Sintática**: Parser Lark automaticamente constrói a AST baseada na gramática EBNF
  - **Análise Semântica**: Implementada nas classes de nós AST (linhas 117-350) com verificação de tipos e contexto
  - **Interpretação/Execução**: Método `evaluate()` e `execute()` em cada nó AST (linhas 350-600)

- **`warpy_linter.py`**: Análise estática e detecção de erros
  - Verificação de sintaxe, variáveis não declaradas, tipos incompatíveis
  - Sistema de códigos de erro estruturado

- **`warpy_grammar.py`**: Definição da gramática em formato isolado para reutilização

### Estruturas de Dados Principais

- **AST Nodes**: Classes para representar diferentes construções da linguagem
  - `CommandNode`: Execução de comandos
  - `DeclarationNode`: Declaração de variáveis
  - `AssignmentNode`: Atribuição de valores
  - `LoopNode`/`WhileLoopNode`: Estruturas de repetição
  - `ConditionalNode`: Estruturas condicionais
  - Nós de expressões aritméticas (`SumNode`, `SubtractionNode`, etc.)

- **Context**: Dicionário para armazenamento de variáveis e estado durante execução

### Etapas de Compilação

1. **Análise Léxica**: Lark tokeniza o código fonte baseado na gramática
2. **Análise Sintática**: Lark constrói a AST automaticamente
3. **Transformação**: `WarpyTransformer` converte a AST Lark em nós customizados
4. **Análise Semântica**: Verificação de tipos e contexto durante a transformação
5. **Interpretação**: Execução através do método `execute()` do nó raiz

## Bugs/Limitações/Problemas Conhecidos

### Limitações Atuais

1. **Sistema de Tipos Simples**: Apenas verificação básica de tipos, sem inferência automática
2. **Escopo de Variáveis**: Apenas escopo global, sem suporte a escopos locais em funções
3. **Estruturas de Dados**: Não há suporte para arrays, structs ou objetos complexos
4. **Funções Definidas pelo Usuário**: Apenas comandos pré-definidos, sem definição de funções customizadas
5. **Sistema de Módulos**: Não há suporte para importação de outros arquivos WarPy40K

### Problemas Conhecidos

1. **Tratamento de Erros**: Algumas mensagens de erro poderiam ser mais específicas
2. **Performance**: Para scripts muito grandes, a interpretação pode ser lenta
3. **Depuração**: Falta de ferramentas de debug integradas
4. **Loops Infinitos**: Alguns testes podem entrar em loop infinito devido a condições malformadas
5. **Acesso a Atributos**: Sintaxe de ponto (`.`) para acesso a atributos ainda não implementada
6. **Operadores Lógicos Complexos**: Expressões lógicas aninhadas podem causar problemas de parsing
7. **Comentários em Linha**: Comentários no meio de expressões podem interferir no parsing

### Melhorias Incrementais Sugeridas

1. **Melhor Tratamento de Erros**: Adicionar números de linha nas mensagens de erro
2. **Escopo de Variáveis**: Implementar pilha de contextos para escopos aninhados
3. **Novos Tipos**: Adicionar tipos `array` e `map` para estruturas de dados
4. **Modo Debug**: Adicionar flag `--debug` para execução passo-a-passo
5. **Otimizações**: Cache de AST para arquivos não modificados
6. **Documentação**: Melhorar documentação inline e exemplos
7. **Timeout para Testes**: Implementar timeout automático para prevenir loops infinitos
8. **Acesso a Atributos**: Implementar sintaxe de ponto para objetos e estruturas
9. **Melhor Suporte a Strings**: Expandir operações com strings e interpolação
10. **Sistema de Imports**: Permitir importação de outros módulos WarPy40K

## Estrutura do Projeto

- `warpy_interpreter.py`: Interpretador e lógica de execução
- `warpy_linter.py`: Linter para análise estática
- `tests/`: Scripts de exemplo incluindo testes aritméticos
- `warpy40k-syntax/`: Extensão de destaque de sintaxe para VS Code
- `warpy40k-sublime/`: Extensão de destaque de sintaxe para Sublime Text

## Contribuições

Contribuições são bem-vindas! Por favor, consulte os READMEs do linter e das extensões de sintaxe para diretrizes de extensão.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes completos.

---

*Pelo Imperador!*

```text
                                                                                                                                                             
        @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@                                   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@        
          @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@                                       @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@          
           @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@@@        @@@@@@@@@@@@   @@@@@@@@@@@@        @@@@@@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@           
            @@@@@@                 @@@@@@@@@@@@@@@@@@@@@@@@          @@@@@@@@@@        @@@@@@@@@          @@@@@@@@@@@@@@@@@@@@@@@@                 @@@@@@            
               @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@       @@@@@@@@@@@@@@@@    @@@@@@@@@@@@@@@       @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@               
                @@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@@@@@        @@@@@@ @@@@@@@@@@@@@@@@@@@  @@@@@        @@@@@@@@@@   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@                
                 @@@@@@@@@@@@@@@@@       @@@@@@@@@@@@@@@@@         @       @@@@@@@@@@@@@@@       @         @@@@@@@@@@@@@@@@@       @@@@@@@@@@@@@@@@@                 
                   @@@@@          @@@@@@@@@@@@@@@@@@@@@@@@@               @@@@@@@@@@@@@@@@@               @@@@@@@@@@@@@@@@@@@@@@@@@          @@@@@                   
                          @@@@@@@@@@@@@@@@@@@@  @@@@@@@@@@@@@        @@@@@@@@@@@@@@@@@@@@@@@@@@@        @@@@@@@@@@@@@  @@@@@@@@@@@@@@@@@@@@                          
                       @@@@@@@@@@@@@@@@@@    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@    @@@@@@@@@@@@@@@@@@                       
                         @@@@@@@@@@@@    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@    @@@@@@@@@@@@                         
                           @@@@@      @@@@@@@@@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@  @@@@@@@@@@@       @@@@                           
                                  @@@@@@@@@@@@   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   @@@@@@@@@@@@                                  
                               @@@@@@@@@@@@@   @@@@@@@ @@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@ @@@@@ @@@@@@@   @@@@@@@@@@@@@                               
                                 @@@@@@@@    @@@@@@@  @@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@ @@@@@@ @@@@@@@    @@@@@@@@                                 
                                   @@@     @@@@@@@@ @@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ @@@@@@@@@@@@ @@@@@@@@     @@@                                   
                                         @@@@@@@@  @@@@@@@ @@@@@     @@@@@ @@@@@@@@@@@@@@@@@@@@@     @@@@@ @@@@@@@  @@@@@@@@                                         
                                         @@@@@@@  @@@@@@@ @@@@@         @@@@@@@@@@@@@@@@@@@@@         @@@@@ @@@@@@@  @@@@@@@                                         
                                            @@   @@@@@@@  @@             @@@@@@@@@@@@@@@@@@@             @@  @@@@@@@   @@                                            
                                                 @@@@@@                  @@@@@@@@@@@@@@@@@@@                  @@@@@@                                                 
                                                                        @@@@@@@@@@@@@@@@@@@@@                                                                        
                                                                       @@@@@@@@@@@@@@@@@@@@@@@                                                                       
                                                                      @@@@@ @@@@@@@@@@@@@@@@@@@   @                                                                  
                                                                 @@@@@@@@  @@@@@@@@@@@@@@@ @@@@@@@@@@                                                                
                                                                 @@@@@@@@   @@@@@@@@@@@@@@  @@@@@ @@                                                                 
                                                                 @@@@@ @@@@  @@@@@@@@@@@ @@@@@ @@@ @                                                                 
                                                                 @@@@  @@@     @@@@@@@   @@@@@ @@@@                                                                  
                                                                 @@@ @@          @@@             @@@                                                                 
                                                                @@@@                            @@@@                                                                 
                                                                   @@                          @@                                                                    