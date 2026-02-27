# 🪖 SGC - Sistema de Gestão de Cautela (Versão Tática)

O **SGC** é uma aplicação web leve e eficiente desenvolvida para modernizar o controle de saída e entrada de materiais em reservas de armamento militares. O projeto substitui as tradicionais fichas de papel por um sistema digital intuitivo, seguro e focado na prontidão operacional.

---

## 🚀 Funcionalidades Principais

-   **📦 Gestão de Arsenal:** Cadastro, edição e exclusão de armamentos diretamente pela interface.
-   **🔍 Scanner de QR Code:** Integração com a câmera para identificação rápida de materiais, evitando erros de digitação.
-   **🖋️ Assinatura Digital:** Campo de assinatura manual integrado para validação da cautela pelo militar receptor.
-   **⚠️ Alerta de Pernoite:** Monitoramento em tempo real com alertas visuais (cards piscantes) e sonoros para materiais não devolvidos após o horário de recolhimento definido.
-   **🔋 Controle de Munição:** Registro específico da quantidade de munições e carregadores acautelados.
-   **📄 Relatórios em PDF:** Geração instantânea de relatórios táticos para passagem de serviço e conferência.
-   **💾 Persistência Local:** Utiliza *LocalStorage* para manter os dados salvos no navegador, sem necessidade de banco de dados externo.
-   **📱 Responsividade Total:** Design tático (Dark Mode) adaptável para computadores, tablets e smartphones.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web puras (Vanilla), garantindo leveza e portabilidade:

-   **HTML5:** Estruturação semântica.
-   **CSS3:** Layout moderno com Flexbox, Grid e animações de alerta.
-   **JavaScript (ES6+):** Lógica de negócio, manipulação de DOM e persistência de dados.
-   **Bibliotecas Externas:**
    -   [Html5-QRCode](https://github.com/mebjas/html5-qrcode): Para leitura de códigos via câmera.
    -   [jsPDF](https://github.com/parallax/jsPDF): Para geração dos relatórios em PDF.

---

## 📸 Como Testar

1.  Acesse o link do projeto (ex: GitHub Pages).
2.  No painel **Arsenal**, cadastre uma nova arma (Ex: Fuzil IA2, SN: EB123).
3.  No painel **Registro**, insira o número de série, o nome do militar e assine na tela.
4.  Defina o **Horário de Recolhimento** no topo para um horário que já passou e observe o alerta visual e sonoro de atraso.

---

## 👨‍💻 Autor

Desenvolvido por **Icaro.taylam**.

> "A tecnologia a serviço da operacionalidade." 🇧🇷

---

### Licença
Este projeto é para fins de estudo e portfólio. Sinta-se à vontade para contribuir ou sugerir melhorias.
