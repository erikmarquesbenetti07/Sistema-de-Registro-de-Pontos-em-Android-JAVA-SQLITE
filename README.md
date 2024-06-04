```markdown
# Sistema de Registro de Pontos em Android

Este é um projeto Android para um sistema simples de registro de pontos de funcionários. O sistema permite que os usuários registrem os horários de entrada e saída, armazenem esses registros em um banco de dados SQLite e visualizem os registros de pontos. Além disso, o sistema também calcula o total de horas trabalhadas.

## Funcionalidades

- **Registro de Pontos**: Registra os horários de entrada e saída dos funcionários.
- **Armazenamento de Dados**: Utiliza SQLite para armazenar os registros de pontos.
- **Exibição de Pontos Registrados**: Exibe os registros de pontos em uma interface de lista.
- **Cálculo de Horas Trabalhadas**: Calcula o total de horas trabalhadas com base nos registros.
- **Exclusão de Pontos**: Permite a exclusão de registros de pontos.

## Tecnologias Utilizadas

- **Linguagem de Programação**: Java
- **IDE**: Android Studio
- **Banco de Dados**: SQLite
- **Componentes de UI**: ConstraintLayout, LinearLayout, RecyclerView, TextView, Button, EditText
- **Bibliotecas**: AndroidX

## Estrutura do Projeto

O projeto é organizado em pacotes e arquivos conforme a convenção do Android. A estrutura principal inclui:

- **`MainActivity.java`**: Tela principal onde os pontos são registrados.
- **`ViewPontosActivity.java`**: Tela onde os pontos registrados são visualizados.
- **`DatabaseHelper.java`**: Classe para criação e gerenciamento do banco de dados SQLite.
- **`PontoDAO.java`**: Classe de acesso aos dados, contendo métodos para inserir e recuperar registros.
- **`Ponto.java`**: Classe modelo representando um ponto registrado.
- **`PontosAdapter.java`**: Adapter para exibir os registros de pontos em um RecyclerView.

## Configuração e Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Abra o projeto no Android Studio**:
   - Abra o Android Studio.
   - Selecione "Open an existing Android Studio project".
   - Navegue até o diretório onde o repositório foi clonado e selecione-o.

3. **Construa o projeto**:
   - Vá para `Build > Clean Project`.
   - Em seguida, vá para `Build > Rebuild Project`.

4. **Execute o projeto**:
   - Conecte um dispositivo Android ou inicie um emulador.
   - Clique no ícone de "Run" ou use o atalho `Shift + F10`.

## Uso

### Registro de Pontos

Na `MainActivity`, o usuário pode registrar os horários de entrada e saída clicando no botão "Bater Ponto". O sistema alterna entre registros de entrada e saída automaticamente.

### Visualização de Pontos

Na `ViewPontosActivity`, os registros de pontos são exibidos em um `RecyclerView`. O total de horas trabalhadas também é exibido.

### Exclusão de Pontos

Cada item na lista de pontos possui um botão "Excluir". Quando clicado, o ponto correspondente é removido do banco de dados e a lista é atualizada.

## Contribuição

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma nova branch: `git checkout -b minha-branch`
3. Faça suas alterações e commit: `git commit -m 'Minhas alterações'`
4. Faça push para a branch: `git push origin minha-branch`
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.
