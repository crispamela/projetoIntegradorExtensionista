# Sistema de cadastro de produtos
Este é um sistema de cadastro de produtos feito para funcionar em um navegador web. Ele foi feito usando HTML, CSS, JavaScript, PHP e o MySQL como banco de dados.

# Requisitos
Ter o XAMPP instalado.

# Instalação
Para instalar esse projeto você pode clonar o repositório:

```
git clone https://github.com/crispamela/projetoIntegradorExtensionista.git
```

É necessário ter um banco de dados com o nome `cadastroProdutos`, e dentro dele deve ter a tabela `produtos`, para cria-lá use:

```
CREATE TABLE produtos (
    id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    quantidade INT NOT NULL,
    valor DECIMAL(10,2) NOT NULL
)
```
