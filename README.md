# 🧮 Gerador e Validador de CPF em Python

Este projeto inclui duas funções principais em Python:
- **Geração de CPF válido**
- **Validação de CPF informado pelo usuário**

Tudo implementado com base no algoritmo oficial dos dígitos verificadores. Ideal para **testes, automações, aprendizado ou validação de formulários**.

## 🚀 Funcionalidades

- Gerar CPF com ou sem formatação
- Validar CPFs digitados, incluindo entrada com pontos/traço
- Tratamento para CPFs inválidos ou repetitivos
- Código modular e reutilizável

## 📦 Como usar

1. Clone o projeto ou copie o arquivo `cpf_utils.py`

2. Exemplo de uso:

```python
from cpf_utils import gerar_cpf, validar_cpf

cpf = gerar_cpf(formatado=True)
print("CPF Gerado:", cpf)

cpf_teste = "123.456.789-09"
if validar_cpf(cpf_teste):
    print("CPF válido!")
else:
    print("CPF inválido!")
```

## 📁 Estrutura

```bash
cpf-util/
├── cpf_utils.py
├── README.md
```

## ⚠️ Aviso Legal

Este projeto é apenas para **fins educacionais e de teste**. O uso de CPFs gerados para fraudes, golpes ou qualquer atividade ilegal **é crime**.

## ✍️ Autor

Desenvolvido por [Henrique Poletti](https://github.com/polettih).  
Sinta-se à vontade para contribuir com melhorias!
