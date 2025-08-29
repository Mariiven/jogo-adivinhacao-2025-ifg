# 🎯 Jogo de Adivinhação

Um projeto interativo de adivinhação desenvolvido em HTML, CSS e JavaScript como atividade avaliativa do curso de Áudio e Vídeo.

## 📋 Sobre o Projeto

Este é um jogo web educacional onde o jogador deve adivinhar um número secreto gerado aleatoriamente. Desenvolvido como parte do currículo do segundo ano do curso técnico, o projeto aplica conceitos fundamentais de desenvolvimento web e lógica de programação.

### 🎮 Como Funciona

- Ao carregar a página web, um número secreto é sorteado automaticamente
- O jogador insere suas tentativas através de uma interface intuitiva
- O sistema fornece feedback indicando se o número é maior ou menor
- O jogador possui um número limitado de tentativas para acertar
- Interface responsiva com feedback visual em tempo real

## 🎓 Contexto Acadêmico

- **Instituição**: IFG - Instituto Federal de Goiás, Câmpus Cidade de Goiás
- **Curso**: Técnico em Áudio e Vídeo
- **Disciplina**: Projeto de Games
- **Período**: Segundo Ano - 2025
- **Tipo**: Atividade Avaliativa

## 🚀 Tecnologias Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

- **HTML5**: Estruturação semântica da interface
- **CSS3**: Estilização, layout responsivo e animações
- **JavaScript**: Lógica do jogo, geração aleatória e interatividade

## ⚡ Funcionalidades

- ✅ Geração aleatória de números secretos
- ✅ Interface web responsiva e moderna
- ✅ Sistema inteligente de dicas (maior/menor)
- ✅ Contador dinâmico de tentativas
- ✅ Feedback visual e interativo
- ✅ Opção de reiniciar partida
- ✅ Validação de entrada do usuário
- ✅ Design adaptável para dispositivos móveis

## 🎯 Como Jogar

1. **Iniciar**: Abra o arquivo `index.html` em qualquer navegador moderno
2. **Inserir**: Digite um número no campo de entrada
3. **Tentar**: Clique no botão "Tentar" ou pressione Enter
4. **Acompanhar**: Observe as dicas fornecidas pelo sistema
5. **Persistir**: Continue tentando até acertar ou esgotar as chances
6. **Recomeçar**: Use o botão "Nova Partida" para reiniciar

## 📁 Estrutura do Repositório

```
jogo-adivinhacao/
├── 📄 index.html          # Interface principal do jogo
├── 🎨 styles/
│   └── style.css          # Folhas de estilo e responsividade
├── ⚙️ scripts/
│   └── game.js            # Lógica do jogo e interações
├── 📚 docs/
│   └── README.md          # Documentação do projeto
└── 🎯 assets/             # Recursos multimídia
    ├── images/            # Imagens e ícones
    └── sounds/            # Efeitos sonoros (se implementados)
```

## 🛠️ Instalação e Execução

### Método 1: Download Direto
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/jogo-adivinhacao.git

# Navegue para o diretório
cd jogo-adivinhacao

# Abra o index.html no navegador
```

### Método 2: Servidor Local (Recomendado)
```bash
# Se usar Python 3
python -m http.server 8000

# Se usar Node.js (npx)
npx serve .

# Se usar VS Code
# Instale a extensão "Live Server" e clique com botão direito no index.html
```

## 🔧 Configurações Personalizáveis

O jogo oferece parâmetros ajustáveis no arquivo `scripts/game.js`:

```javascript
// Configurações do jogo
const CONFIG = {
    MIN_NUMBER: 1,           // Número mínimo
    MAX_NUMBER: 100,         // Número máximo
    MAX_ATTEMPTS: 7,         // Tentativas permitidas
    DIFFICULTY: 'normal'     // Nível de dificuldade
};
```

## 📊 Objetivos de Aprendizagem

Este projeto foi desenvolvido para consolidar conhecimentos em:

- **Frontend Development**: HTML5, CSS3 e JavaScript ES6+
- **Lógica de Programação**: Algoritmos, estruturas condicionais e loops
- **Interface de Usuário**: Design responsivo e experiência do usuário
- **Controle de Versão**: Git e GitHub para versionamento
- **Desenvolvimento Web**: Boas práticas e padrões de código
- **Game Design**: Mecânicas básicas de jogos digitais

## 🎨 Processo de Desenvolvimento

O desenvolvimento segue uma abordagem iterativa:

1. **Planejamento**: Definição das regras e mecânicas
2. **Prototipação**: Criação da versão básica funcional
3. **Implementação**: Desenvolvimento das funcionalidades
4. **Refinamento**: Ajustes de interface e experiência
5. **Testes**: Validação em diferentes navegadores e dispositivos
6. **Documentação**: Criação desta documentação completa

## 🔄 Roadmap de Desenvolvimento

- [x] Estrutura HTML básica
- [x] Estilização CSS responsiva
- [x] Lógica JavaScript fundamental
- [ ] Sistema de pontuação
- [ ] Níveis de dificuldade
- [ ] Efeitos sonoros
- [ ] Animações CSS avançadas
- [ ] Modo multiplayer local
- [ ] Histórico de partidas

## 🤝 Contribuições Acadêmicas

Este é um projeto educacional, mas sugestões são bem-vindas:

- 🐛 Reportar problemas encontrados
- 💡 Sugerir melhorias na jogabilidade
- 🎨 Propor aprimoramentos visuais
- 📖 Contribuir com a documentação

## 📈 Competências Desenvolvidas

- **Técnicas**: HTML5, CSS3, JavaScript, Git
- **Metodológicas**: Resolução de problemas, pensamento lógico
- **Sociais**: Trabalho em equipe, comunicação técnica
- **Pessoais**: Autonomia, criatividade, persistência

## 🎯 Avaliação e Critérios

O projeto será avaliado considerando:
- Funcionalidade e correção do código
- Qualidade da interface e experiência do usuário
- Organização e documentação do código
- Criatividade e inovação implementadas
- Aplicação dos conceitos aprendidos

## 📞 Informações de Contato

- **Desenvolvedor**: Mariana Ventura de Oliveira
- **Turma**: Segundo Ano - Áudio e Vídeo
- **Email Institucional**: [seu.email@estudante.ifg.edu.br]
- **Período**: 2025.1

## 📄 Licença Educacional

Este projeto foi desenvolvido exclusivamente para fins educacionais como parte do currículo do curso técnico em Áudio e Vídeo do IFG.

---

<div align="center">

⭐ **Projeto desenvolvido com dedicação para o aprendizado em desenvolvimento web** ⭐

*Instituto Federal de Goiás - Câmpus Cidade de Goiás*  
*Curso Técnico em Áudio e Vídeo - 2025*

</div>
