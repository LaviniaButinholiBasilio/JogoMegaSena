# 🎰 Jogo da Loteria (Sena) - Python Terminal

![Feito com Python](https://img.shields.io/badge/feito%20com-Python-FFC0CB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-concluído-FFC0CB)
![Licença](https://img.shields.io/badge/licença-Livre-FFC0CB)
![Autoria](https://img.shields.io/badge/feito%20por-Lavínia%20Butinholi%20Basílio-FFC0CB)


---

## 📖 Descrição
Este projeto implementa um **simulador de Loteria (Sena)** em Python.  
O programa sorteia 6 números aleatórios entre 1 e 60 e permite que o usuário faça apostas, conferindo quantos números acertou.  
O jogo identifica acertos especiais: **Quadra (4 acertos), Quina (5 acertos) e Sena (6 acertos)**.  

É ideal para estudo de **loops, listas, validação de entradas** e **randomização** em Python.

---

## ⚙️ Funcionalidades
- 🔹 Sorteio aleatório de 6 números (1 a 60)  
- 🎯 Permite apostas do usuário  
- ✅ Verifica acertos e identifica Quadra, Quina ou Sena  
- 💻 Interface simples via terminal  
- 🚨 Validação de entradas e números repetidos  

---

## 🧠 Estrutura do Código
| Variável/Função | Descrição |
|-----------------|------------|
| `sorteio` | Lista com os 6 números sorteados aleatoriamente |
| `vetor` | Valores das apostas de acordo com a quantidade de números escolhidos |
| `num_apostas` | Quantidade de números que o usuário quer apostar |
| `aposta` | Lista com os números escolhidos pelo usuário |
| `acertos` | Contador de números acertados |
| `num_acertados` | Lista com os números acertados pelo usuário |

---


## 👩‍💻 Autor

**Lavínia Butinholi Basílio**  

Sou desenvolvedora apaixonada por tecnologia e aprendizado. Este projeto foi criado como estudo prático em **listas, loops e randomização em Python**, com o objetivo de **simular sorteios de forma educativa e divertida**.

---


## 🪶 Licença

Este projeto é de **uso livre** para fins **educacionais e de aprendizado**.  

Você pode estudar, modificar e aprimorar o código à vontade, explorando conceitos de **programação em Python** de forma prática.

---


## 🎮 Como Jogar

Para jogar, siga os passos abaixo:  

1. Execute o programa.  
2. Informe a **quantidade de números que deseja apostar**, entre 6 e 20.  
3. Escolha os números da sua aposta, garantindo que cada número seja **entre 1 e 60** e **não se repita**.  
4. O programa sorteia 6 números aleatórios e compara com os números escolhidos pelo usuário.  
5. Ao final, você verá:
   - Quantos números acertou  
   - Quais números foram acertados  
   - Se houve resultado especial: **Quadra (4 acertos)**, **Quina (5 acertos)** ou **Sena (6 acertos)**  

Este texto serve como **guia direto**, sem usar blocos de código, facilitando a leitura no GitHub.

---


## 🚀 Como Executar

### 1️⃣ Pré-requisitos
- Ter o **Python 3** instalado no sistema

### 2️⃣ Clonar o repositório
```bash
git clone https://github.com/seuusuario/jogo-loteria-sena.git
cd jogo-loteria-sena
python loteria_sena.py

