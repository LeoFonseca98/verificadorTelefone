```markdown
# Verificador de Localidade de Telefone

Este projeto, desenvolvido durante uma aula da Digital Innovation One (DIO), utiliza a biblioteca `phonenumbers` para identificar a localidade de um número de telefone informado pelo usuário.

## 📝 Descrição

O programa solicita ao usuário que insira um número de telefone no formato internacional (exemplo: `+551140028922`). Em seguida, utiliza a biblioteca `phonenumbers` para determinar a localização associada ao número de telefone informado e exibe o resultado.

## 🚀 Como executar

1. Certifique-se de que o Python esteja instalado no seu computador.
2. Instale a biblioteca `phonenumbers` caso ainda não a tenha:
   ```bash
   pip install phonenumbers
   ```
3. Clone este repositório e execute o script Python:
   ```bash
   python verificar_telefone.py
   ```

4. Insira o número de telefone no formato internacional quando solicitado.

## 📂 Estrutura do Código

O código é estruturado da seguinte forma:
1. Importa a biblioteca `phonenumbers`.
2. Solicita ao usuário um número de telefone no formato internacional.
3. Processa o número de telefone com a função `phonenumbers.parse()`.
4. Exibe a localização do número utilizando `geocoder.description_for_number`.

## 🛠 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **phonenumbers**: Biblioteca para manipulação e análise de números de telefone.

## 📚 Referências

- [Documentação do phonenumbers](https://pypi.org/project/phonenumbers/)

## 🏫 Créditos

Este código foi desenvolvido durante uma aula prática da **Digital Innovation One (DIO)**.
```
