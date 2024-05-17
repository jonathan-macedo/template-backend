# Guia de Contribuição

[![Star](https://img.shields.io/github/stars/jonathan-macedo/portfolio-backend?style=social)](https://github.com/jonathan-macedo/portfolio-backend/stargazers)
[![Forks](https://img.shields.io/github/forks/jonathan-macedo/portfolio-backend?style=social)](https://github.com/jonathan-macedo/portfolio-backend/forks)
[![GitHub Issues](https://img.shields.io/github/issues/jonathan-macedo/portfolio-backend?style=social)](https://github.com/jonathan-macedo/portfolio-backend/issues/)

Fique a vontade para ajudar no meu aprendizado e no seu também. Caso tenha alguma dúvida sobre a construção do projeto, entre em contato comigo pelo [LinkedIn](https://www.linkedin.com/in/jonathan-macedo-castro/).

⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**)

## Instruções

1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEU_USERNAME/portfolio-backend.git`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/jonathan-macedo/portfolio-backend.git`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar.
4. Crie uma nova **branch**:
5. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: adicionar uma função de verificação"`;
    > **Observação:** Verificar a Convenção de Commits para escrever a mensagem do seu commit de forma clara e padronizada.
6. Envie as alterações para o seu repositório remoto;
    > **Observação:** Você pode utilizar o comando `git push origin` para mandar as alterações sem precisar especificar a URL, desde que você tenha feito o passo **3**.
7. Crie um **Pull Request**.
    > **Observação**: No geral, quando você der um push para o seu repositório do Github, ele perguntará para você se deseja fazer um Pull Request.

## <img src="https://user-images.githubusercontent.com/74038190/206662607-d9e7591e-bbf9-42f9-9386-29efc927bc16.gif" width="30px" height="30px"> Convenção de Commits

| Tipo de Commit | Descrição                                                            | Exemplo
| ---------------|----------------------------------------------------------------------|-----------
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                         | `feat: add USENAME.md profile`
| `fix`          | Corrige um bug ou problema no projeto.                               | `fix: fixed issue fix#IssueNumber`
| `docs`         | Altera a documentação do projeto. Ex.: README, comentários no código.| `doc: altered section SECTIONNAME`
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.         | `style: add EFFECTNAME to COMPONENT`
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.         | `refactor: refactor at CLASSNAME`
| `test`         | Adiciona ou modifica testes no projeto.                              | `test: testing FUNCIONALITYNAME`