# Sistema de Gerenciamento de Restaurantes (CLI)

Este projeto é um **aplicativo de linha de comando (CLI)** desenvolvido em Python para gerenciar restaurantes. Ele permite cadastrar novos restaurantes, listar os existentes e alternar seu estado (ativo/desativado) de forma simples e interativa.

---

## 🚀 Funcionalidades

- **Cadastrar restaurante**: Adicione novos restaurantes com nome e categoria.
- **Listar restaurantes**: Visualize todos os restaurantes cadastrados com status (ativado/desativado).
- **Alternar estado**: Ative ou desative restaurantes existentes.
- **Interface amigável**: Menu interativo com navegação simples.

---

## 🛠️ Pré-requisitos

- **Python 3.x**
- Sistema operacional compatível com o comando `cls` (Windows).  
  Para Linux/Mac, substitua `os.system('cls')` por `os.system('clear')`.

---

## ▶️ Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Execute o script:
   ```bash
   python main.py
   ```

3. Escolha uma das opções do menu:
   - `1`: Cadastrar restaurante
   - `2`: Listar restaurantes
   - `3`: Alternar estado do restaurante
   - `4`: Sair

---

## ⚙️ Estrutura do Código

- **Lista inicial de restaurantes**:  
  ```python
  restaurantes = [
      {'nome':'Praça', 'categoria':'Japonesa', 'ativo':False}, 
      {'nome':'Pizza Suprema', 'categoria':'Pizza', 'ativo':True},
      {'nome':'Cantina', 'categoria':'Italiano', 'ativo':False}
  ]
  ```

- **Funções principais**:
  - `cadastrar_novo_restaurante()`: Adiciona um novo restaurante.
  - `listar_restaurantes()`: Exibe todos os restaurantes.
  - `alternar_estado_restaurante()`: Alterna o estado ativo/desativado.
  - `main()`: Função principal que exibe o menu e controla a navegação.

---

## 🖥️ Exemplo de Saída

```
░██████╗░█████╗░██████╗░░█████╗░██████╗░
██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔══██╗
╚█████╗░███████║██████╦╝██║░░██║██████╔╝
░╚═══██╗██╔══██║██╔══██╗██║░░██║██╔══██╗
██████╔╝██║░░██║██████╦╝╚█████╔╝██║░░██║
╚═════╝░╚═╝░░╚═╝╚═════╝░░╚════╝░╚═╝░░╚═╝

1. Cadastrar restaurante
2. Listar restaurantes
3. Alternar estado do restaurante
4. Sair
```

---

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
 
