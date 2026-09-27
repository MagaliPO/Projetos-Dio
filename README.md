# 📈 Projeto Ferramentas de Controle de Investimentos com Excel - Simulação de Investimentos em FIIs

Este projeto foi desenvolvido a partir de uma planilha Excel para simular aportes mensais em **Fundos Imobiliários (FIIs)**, considerando diferentes perfis de investidor e cenários de dividendos.

---

## ⚙️ Configurações
- **Salário:** R$ 15.000  
- **Investimento mensal:** R$ 3.000  
- **Duração:** 3 anos (36 meses)  
- **Taxa de rendimento mensal:** 1%  
- **Perfil escolhido:** Agressivo  

---

## 📐 Fórmulas de Cálculo

### Patrimônio acumulado


\[
FV = P \cdot \frac{(1+i)^n - 1}{i}
\]



- \(FV\) = Valor futuro (patrimônio acumulado)  
- \(P\) = Aporte mensal (R$ 3.000)  
- \(i\) = Taxa de rendimento mensal (0,01 = 1%)  
- \(n\) = Número de meses (36)  

Exemplo:  


\[
FV = 3000 \cdot \frac{(1+0,01)^{36} - 1}{0,01}
\]



---

### Dividendos mensais


\[
D = FV \cdot y
\]



- \(D\) = Dividendos mensais  
- \(FV\) = Patrimônio acumulado  
- \(y\) = Taxa de dividendos (ex.: 0,02 = 2%)  

---

## 📊 Cenários de Dividendos
- **2 anos:** R$ 5  
- **5 anos:** R$ 10  
- **10 anos:** R$ 20  
- **20 anos:** R$ 30  
- **30 anos:** (a calcular)  

---

## 👤 Perfis de Investidor e Alocação de FIIs

| Perfil       | Papel | Tijolo | Híbridos | FOFs | Desenvolvimento | Hotelarias |
|--------------|-------|--------|----------|------|-----------------|------------|
| Conservador  | 20%   | 50%    | 10%      | 10%  | 10%             | 0%         |
| Moderado     | 22%   | 55%    | 8%       | 5%   | 5%              | 5%         |
| Agressivo    | 5%    | 60%    | 5%       | 5%   | 20%             | 5%         |

---

## 🧱 Imagem de referência
A imagem de **tijolos** utilizada no projeto está disponível em:  
[https://pt.pngtree.com/freepng/isolated-stack-of-red-bricks_20340923.html](https://pngtree.com)

---

## 🎨 Paleta de Cores Utilizada
- `#97755C`  
- `#D0966B`  
- `#BAAB87`  
- `#D6C2AA`  
- `#AAD2C8`  
- `#6A8577`  

---

## 🎯 Objetivo
Este projeto simula diferentes cenários de investimento em FIIs, considerando perfis de risco, dividendos ao longo do tempo e a diversificação da carteira.

