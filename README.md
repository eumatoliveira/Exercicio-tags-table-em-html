# Tabela HTML com Hora Atual e Estilização

Este guia demonstra como criar uma tabela HTML que exibe a hora atual, como estilizar a tabela usando CSS, e como aplicar os princípios SOLID e Clean Code.

## Instalação do Repositório

1.  **Clone o repositório:**
    ```bash
    git clone <URL_do_repositório>
    cd <nome_do_repositório>
    ```

2.  **Abra o arquivo `index.html` em um navegador da web.**

## Estrutura do Projeto

* `index.html`: Estrutura HTML da tabela.
* `style.css`: Estilos CSS para a tabela.
* `script.js`: Código JavaScript para obter e exibir a hora atual.

## Estrutura HTML (`index.html`)

```html
<!DOCTYPE html>
<html>
<head>
    <title>Tabela com Hora Atual</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Propriedade</th>
                <th>Valor</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Hora Atual</td>
                <td id="horaAtual"></td>
            </tr>
        </tbody>
    </table>
    <script src="script.js"></script>
</body>
</html>
