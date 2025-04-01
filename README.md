# Modelo de Vicsek - Simulação em Python

Este projeto implementa uma simulação do **modelo de Vicsek**, um modelo clássico que descreve o movimento coletivo de partículas autônomas, como pássaros ou peixes, que interagem localmente e exibem comportamento emergente.

## 📌 Descrição
O modelo simula partículas que:
- Movem-se com velocidade constante dentro de uma caixa bidimensional.
- Ajustam sua direção com base nos vizinhos próximos dentro de um raio de interação definido.
- Sofrem perturbações aleatórias para simular ruído ambiental.
- Possuem condições de contorno periódicas, ou seja, partículas que ultrapassam os limites da caixa reaparecem no lado oposto.

A simulação é exibida em tempo real usando gráficos vetoriais com a biblioteca `matplotlib`.

## 🚀 Funcionalidades
- Simulação de movimento coletivo de partículas.
- Visualização em tempo real das partículas e suas direções.
- Suporte para condições de contorno periódicas.
- Configuração personalizável de parâmetros como velocidade, ruído, tamanho da caixa e número de partículas.

## 📂 Estrutura do Projeto
```
.
├── activematter.png  # Imagem gerada pela simulação
├── main.py           # Código principal da simulação
├── README.md         # Documentação do projeto
```

## 📦 Dependências
- Python 3.x
- NumPy
- Matplotlib

Instale as dependências executando:
```bash
pip install numpy matplotlib
```

## 🔑 Como executar
1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
```
2. Acesse o diretório do projeto:
```bash
cd nome-do-repositorio
```
3. Execute o script principal:
```bash
python main.py
```

## 📈 Parâmetros do Modelo
- `v0`: Velocidade constante das partículas.
- `eta`: Intensidade do ruído aleatório aplicado aos ângulos de movimento.
- `L`: Tamanho da caixa.
- `R`: Raio de interação entre partículas.
- `dt`: Intervalo de tempo entre atualizações.
- `Nt`: Número de iterações da simulação.
- `N`: Número de partículas.

Projeto criado em Python na materia de Tópicos Avançados de Sistemas da informação.
