# Questionário Interativo

## Descrição

Este projeto implementa um questionário interativo com interface gráfica customizada, utilizando a biblioteca Customtkinter. O programa oferece uma experiência de quiz dinâmica e personalizável, ideal para uso educacional ou em apresentações.

## Características Principais

- Interface gráfica moderna e responsiva
- Seleção aleatória de questões a partir de um arquivo JSON
- Temporizador para cada questão com barra de progresso visual
- Configuração flexível do número de questões e tempo por questão
- Seleção aleatória de alunos para participação
- Feedback imediato após cada resposta
- Resultados finais exibidos ao término do questionário

## Pré-requisitos

- Python 3.x
- Bibliotecas: customtkinter, pandas

## Instalação

1. Clone o repositório:
2. Navegue até o diretório do projeto:
cd questionario-interativo


3. Instale as dependências:
pip install -r requisitos.txt


## Uso

Execute o script principal:

python questionario.py


Siga as instruções na interface gráfica para configurar e iniciar o questionário.

## Estrutura do Projeto

- `questionario.py`: Script principal contendo toda a lógica do programa
- `pergunta.json`: Arquivo JSON com as questões, alternativas e respostas corretas
- `alunos.json`: Arquivo JSON com a lista de alunos para seleção aleatória

## Configuração

As principais configurações podem ser ajustadas no início do script:

- `NUM_QUESTOES`: Número de questões no questionário (padrão: 5)
- `TEMPO_QUESTAO`: Tempo em segundos para responder cada questão (padrão: 10)

## Funcionalidades

### Menu Principal
- Iniciar questionário
- Acessar configurações
- Selecionar aluno aleatoriamente
- Sair do programa

### Configurações
- Ajustar número de questões
- Definir tempo por questão

### Questionário
- Exibição de questões aleatórias
- Temporizador por questão
- Feedback imediato após resposta

### Resultados
- Exibição do número de acertos
- Opção de retorno ao menu principal

## Contribuindo

Contribuições são bem-vindas! Por favor, siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Faça commit das suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Contato

Seu Nome - [@seutwitter](https://twitter.com/seutwitter) - email@example.com

Link do Projeto: [https://github.com/seu-usuario/uestionario-interativo](https://github.com/seu-usuario/questionario-interativo)