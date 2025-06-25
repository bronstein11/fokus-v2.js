# 🎯 Fokus V2 - Aplicativo de Produtividade

Um aplicativo web de produtividade baseado na técnica Pomodoro, desenvolvido para otimizar o foco e gerenciamento de tarefas com uma interface moderna e intuitiva. Esta é a **versão 2** do Fokus, que expande significativamente as funcionalidades da versão original.

## 🔗 Demo
- **Fokus V2** (com gerenciamento de tarefas): [https://fokus-v2-js-uuli.vercel.app/](https://fokus-v2-js-uuli.vercel.app/)
- **Fokus V1** (apenas timer): [https://fokus-js-phi.vercel.app/](https://fokus-js-phi.vercel.app/)

## 📋 Sobre o Projeto

O **Fokus V2** é uma evolução significativa da versão original, combinando timer personalizado com um sistema completo de gerenciamento de tarefas. Enquanto a V1 focava apenas no timer Pomodoro, esta versão adiciona funcionalidades avançadas de produtividade.

## 🆕 Novidades da V2

### 📝 **Sistema Completo de Tarefas** (Novo!)
- ✅ Adicionar, editar e remover tarefas
- ✅ Seleção de tarefa ativa durante sessões de foco
- ✅ Conclusão automática de tarefas após sessão de foco
- ✅ Persistência de dados no localStorage
- ✅ Limpeza de tarefas concluídas ou todas as tarefas
- ✅ Interface intuitiva com dropdown de ações

### 🔄 **Integração Timer + Tarefas** (Novo!)
- ✅ Sincronização entre timer e tarefa selecionada
- ✅ Eventos customizados para comunicação entre módulos
- ✅ Atualização automática do status das tarefas

### 🎨 **Interface Aprimorada** (Novo!)
- ✅ Seção dedicada para gerenciamento de tarefas
- ✅ Indicadores visuais de tarefa ativa e concluída
- ✅ Sistema de cores diferenciado para status das tarefas

## ✨ Funcionalidades Completas

### ⏱️ Timer Pomodoro (V1 + Melhorias)
- **Foco**: 25 minutos de concentração
- **Descanso Curto**: 5 minutos de pausa  
- **Descanso Longo**: 15 minutos de relaxamento
- Interface visual que muda de acordo com o contexto selecionado
- Sons de feedback para play, pause e conclusão
- Música de fundo opcional durante as sessões

### 📝 Gerenciamento de Tarefas (NOVO na V2!)
- **Adicionar tarefas**: Interface intuitiva com textarea
- **Editar tarefas**: Edição rápida via prompt
- **Selecionar tarefa ativa**: Vincular tarefa ao período de foco
- **Conclusão automática**: Tarefas são marcadas como concluídas após sessão de foco
- **Remover tarefas**: Opções para limpar tarefas concluídas ou todas
- **Persistência**: Dados salvos automaticamente no navegador
- **Estados visuais**: Diferentes cores para tarefas ativas, concluídas e pendentes

### 🔄 Integração Timer + Tarefas (NOVO na V2!)
- **Sincronização**: Tarefa selecionada é exibida durante o timer
- **Eventos customizados**: Comunicação inteligente entre módulos
- **Workflow otimizado**: Fluxo de trabalho integrado e eficiente

### 🎵 Recursos Adicionais (Mantidos da V1)
- Música de fundo opcional durante as sessões
- Design responsivo para diferentes dispositivos  
- Tema visual dinâmico baseado no modo selecionado

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da aplicação
- **CSS3**: Estilização avançada com:
  - Variáveis CSS personalizadas
  - Gradientes e efeitos visuais
  - Design responsivo
  - Animações e transições
- **JavaScript (ES6+)**: 
  - Manipulação do DOM
  - API de armazenamento local
  - Custom Events
  - Audio API para efeitos sonoros

## 🎨 Design e UX

- **Paleta de Cores**: Sistema de cores dinâmico baseado no contexto
- **Tipografia**: Combinação das fontes Montserrat e Unbounded
- **Layout**: Interface centrada e responsiva
- **Interatividade**: Feedback visual e sonoro para todas as ações

## 📱 Responsividade

O aplicativo é totalmente responsivo, adaptando-se a:
- 🖥️ **Desktop**: Layout completo com todos os recursos
- 📱 **Tablets**: (768px - 1024px) Interface otimizada
- 📱 **Mobile**: (até 767px) Layout compacto e touch-friendly

## 🚀 Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/fokus-app.git
   ```

2. **Abra o projeto**:
   - Navegue até a pasta do projeto
   - Abra o arquivo `index.html` no seu navegador
   - Ou acesse a demo online: [https://fokus-v2-js-uuli.vercel.app/](https://fokus-v2-js-uuli.vercel.app/)

3. **Funcionalidades principais**:
   - **Timer**: Selecione o tipo de sessão (Foco, Descanso Curto ou Longo)
   - **Tarefas**: Adicione suas tarefas e selecione uma para focar
   - **Música**: Use o toggle de música conforme preferir
   - **Workflow**: Inicie o timer e concentre-se na tarefa selecionada
   - **Conclusão**: Tarefas são automaticamente concluídas após sessão de foco

## 📂 Estrutura do Projeto

```
fokus-v2/
│
├── index.html              # Página principal
├── styles.css              # Estilos da aplicação  
├── script.js               # Lógica do timer e interface (V1 base)
├── script-crud.js          # Gerenciamento de tarefas (NOVO na V2)
├── imagens/                # Assets visuais
│   ├── logo.png
│   ├── foco.png
│   ├── descanso-curto.png
│   ├── descanso-longo.png
│   ├── play_arrow.png
│   ├── pause.png
│   ├── add_circle.png      # Ícones para tarefas
│   ├── edit.png
│   ├── check.svg
│   ├── trash.svg
│   ├── delete.png
│   ├── close.png
│   ├── save.png
│   ├── more.svg
│   └── pattern.png
└── sons/                   # Efeitos sonoros
    ├── luna-rise-part-one.mp3
    ├── play.wav
    ├── pause.mp3
    └── beep.mp3
```

## 🎯 Técnica Pomodoro

O aplicativo segue os princípios da técnica Pomodoro:
1. Trabalhe com foco por 25 minutos
2. Faça uma pausa curta de 5 minutos
3. Após 4 sessões, faça uma pausa longa de 15 minutos
4. Repita o ciclo

## 💾 Persistência de Dados

As tarefas são automaticamente salvas no `localStorage` do navegador, garantindo que suas informações não sejam perdidas entre sessões.

## 📈 Evolução: V1 → V2

### Fokus V1 (Base)
- ⏱️ Timer Pomodoro com 3 modos
- 🎵 Controle de música de fundo  
- 🎨 Interface responsiva com temas dinâmicos
- 🔊 Efeitos sonoros de feedback

### Fokus V2 (Atual) - Adições
- ➕ **Sistema completo de gerenciamento de tarefas**
- ➕ **Integração timer + tarefas com eventos customizados**
- ➕ **Persistência de dados no localStorage**
- ➕ **Interface expandida com seção dedicada para tarefas**
- ➕ **Estados visuais diferenciados para tarefas**
- ➕ **Conclusão automática após sessões de foco**

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir novas funcionalidades
- Enviar pull requests
- Melhorar a documentação

## 👨‍💻 Autor

**Mauricio Grass de Bronstein**

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
