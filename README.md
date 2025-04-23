
# 🧮 Gerador e Validador de CPF em Python

Este projeto fornece um conjunto de funções para **gerar e validar CPFs** em Python, com base no algoritmo oficial de cálculo dos dígitos verificadores. Ele é ideal para automações, testes, aprendizado ou validação de formulários.

## 🚀 Funcionalidades

- **Geração de CPF**: Criação de CPFs válidos, com ou sem formatação.
- **Validação de CPF**: Verificação da validade de CPFs informados, incluindo suporte a formatos com pontos e traços.
- **Tratamento de CPFs inválidos ou repetitivos**.
- **Código modular e reutilizável**, facilitando a integração em outros projetos.

## 📦 Como Usar

### 1. Clonar ou Instalar via GitHub

Você pode obter o projeto de duas maneiras:

- **Clonando o repositório diretamente:**

```bash
git clone https://github.com/seu-usuario/cpf-utils.git
```

- **Instalando via `pip` diretamente do GitHub** (caso prefira não clonar manualmente):

```bash
pip install git+https://github.com/seu-usuario/cpf-utils.git
```

### 2. Importar e Utilizar as Funções

Após clonar ou instalar, basta importar as funções do módulo `cpf_utils` e utilizá-las conforme seu caso de uso.

### Exemplo de Uso:

```python
from cpf_utils import gerar_cpf, validar_cpf

# Gerar CPF formatado
cpf = gerar_cpf(formatado=True)
print("CPF Gerado:", cpf)

# Validar um CPF
cpf_teste = "123.456.789-09"
if validar_cpf(cpf_teste):
    print("CPF válido!")
else:
    print("CPF inválido!")
```


## 📁 Estrutura do Projeto

```
cpf-utils/
├── cpf_utils/
│   ├── __init__.py       ← Importa as funções aqui
│   └── core.py           ← Código das funções (geração e validação)
├── setup.py              ← Script de instalação
├── README.md
└── LICENSE (opcional)
```



## ⚠️ Aviso Legal

Este projeto é destinado exclusivamente para **fins educacionais e de teste**. O uso de CPFs gerados para práticas fraudulentas, golpes ou qualquer atividade ilegal é crime.



## ✍️ Autor

Desenvolvido por Henrique Poletti. Fique à vontade para contribuir com melhorias ou sugestões!
