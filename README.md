# Contador-Regressivo — Confraternização do TI

Uma página em **HTML + CSS + JavaScript** para exibir uma contagem regressiva animada do evento (ex.: confraternização de fim de ano).  
O projeto inclui neve animada, confete, relógio em tempo real e piadas rotativas de TI.

---

## 🚀 Como rodar

1. Baixe o arquivo `contador_regressivo.html` (ou copie o código abaixo).
2. Abra no navegador (não precisa servidor nem dependências externas).
3. Pronto, a contagem regressiva já aparece.

---

## ⚙️ Personalização

- **Data e hora** → dentro da função `getTargetDate()`  
- **Textos** → `<h1>`, `<h2>` e `.pill`  
- **Tema** → variáveis em `:root` (CSS)  
- **Neve** → quantidade em `snowCount` e símbolos no array `symbols`  
- **Confete** → função `burst(n)` define intensidade  
- **Piadas** → editar array `jokes` no final do script  

---

## ♿ Acessibilidade

- Região da contagem com `aria-live="polite"`.
- Contraste forte.
- Relógio atualizado em tempo real.

---

## 📱 Responsividade

- Fontes e caixas adaptáveis via `clamp()`.
- Layout ajusta para 2 colunas em telas menores (até 720px).

---

<img width="1392" height="749" alt="image" src="https://github.com/user-attachments/assets/249b9efe-447c-46a4-bc98-58b77acf867f" />
