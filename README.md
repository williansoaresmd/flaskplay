# Flaskplay (Flask)

Um app bem simples em **Flask** para eu praticar Python e registrar minha evolução.

## Objetivo do projeto
- Criar um CRUD básico de **jogos** (adicionar, listar, editar, remover)
- Treinar Flask, rotas, templates e formulários
- Registrar **o que eu aprendi por dia** e os **desafios** que enfrentei


### Funcionalidades do APP
- [ ] Adicionar jogo (nome, plataforma, status, nota opcional)
- [ ] Listar jogos cadastrados
- [ ] Editar jogo
- [ ] Remover jogo

### Diário de aprendizado
- [ ] lista por dia: "o que aprendi" + "desafios"
- [ ] Atualizar diariamente

---

## Tecnologias
- Python 3.x
- Flask
- (futuro) SQLite / SQLAlchemy

## 📚 Diário de Aprendizado

### Dia 1

#### O que aprendi
- **Ambiente virtual em Python**
  - Aprendi a trabalhar com ambientes virtuais para isolar dependências de cada projeto.
  - Entendi que isso evita conflitos de versões entre bibliotecas quando tenho mais de um projeto Python no mesmo computador.
  - Compreendi que o ambiente virtual garante que o projeto rode da mesma forma em qualquer máquina.

- **Estrutura inicial de um app em Python (Flask)**
  - Aprendi como iniciar um projeto Flask do zero.
  - Entendi a função do arquivo principal (`app.py` ou `main.py`), das rotas e do ponto de entrada da aplicação.
  - Aprendi a rodar a aplicação localmente usando o servidor de desenvolvimento do Flask.

- **Gerenciamento de dependências**
  - Aprendi a instalar bibliotecas dentro do ambiente virtual.
  - Entendi a importância de registrar dependências em arquivos como `requirements.txt` ou `Pipfile`.

#### Desafios e bugs encontrados
- O curso utilizado é mais antigo, o que gerou **incompatibilidades entre versões** das ferramentas atuais.
- Alguns comandos e bibliotecas apresentados no curso não funcionaram da mesma forma nas versões mais recentes do Python.
- Enfrentei erros relacionados a:
  - Versões do Python não compatíveis com algumas bibliotecas
  - Mudanças em pacotes que deixaram de existir ou foram substituídos
  - Diferenças no comportamento do Flask entre versões

#### O que ficou claro
- Manter versões alinhadas é fundamental para evitar bugs.
- Nem todo erro é “meu código errado”, muitas vezes é **problema de versão ou compatibilidade**.
- Saber ler erros e pesquisar soluções faz parte do aprendizado real em Python.

---

### Dia 2 

#### O que aprendi
- **Organização de arquivos e pastas**
  - Aprendi a organizar o projeto em pastas separadas para melhorar a legibilidade e manutenção do código.
  - Entendi a importância de separar arquivos Python, templates HTML e arquivos estáticos.
  - Isso facilitou entender a estrutura do app e deixou o projeto mais escalável.

- **Uso do `render_template` no Flask**
  - Aprendi a utilizar o `render_template` para renderizar páginas HTML.
  - Entendi como passar variáveis do Python para o HTML e utilizá-las dentro dos templates.
  - Consegui exibir valores dinâmicos no front-end a partir do back-end.

- **Integração de Python com HTML (Jinja)**
  - Aprendi a utilizar arquivos Python no HTML por meio do mecanismo de templates.
  - Usei estruturas de repetição com `for ... in` para listar dados dinamicamente.
  - Entendi como exibir listas e objetos diretamente nos templates.

- **Programação orientada a objetos**
  - Aprendi a utilizar classes para a criação de objetos.
  - Entendi como isso torna o código mais dinâmico, reutilizável e organizado.
  - Consegui representar entidades (como jogos) de forma mais estruturada.

#### Desafios
- Entender a sintaxe do Jinja dentro do HTML exigiu atenção para não confundir com Python puro.
- Ajustar a comunicação entre back-end e front-end foi um desafio inicial.
- Pensar em classes e objetos exigiu mudar a forma de estruturar o código.

#### O que ficou claro
- Organização de pastas impacta diretamente na produtividade.
- Templates tornam o front-end realmente dinâmico.
- Programação orientada a objetos facilita a evolução do projeto conforme ele cresce.

---


  
