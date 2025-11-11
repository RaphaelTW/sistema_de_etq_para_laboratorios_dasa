# 🧾 Sistema de Etiquetas 5x5

O **Sistema de Etiquetas 5x5** é uma aplicação web desenvolvida em **HTML, CSS e JavaScript puro**, projetada para gerar **etiquetas personalizadas de 5x5 cm** utilizadas em **testes de preparo, calibração e controle de amostras**.

A ferramenta permite criar múltiplas etiquetas de forma automatizada, com **QR Codes integrados** e **exportação direta para o formato `.docx` (Word)** — tudo processado diretamente no navegador, **sem necessidade de servidor ou backend**.

---

## ⚙️ Funcionalidades Principais

- ✅ **Geração automática de etiquetas** com tamanho fixo de 5x5 cm.  
- ✅ **Formulário dinâmico** para entrada de dados:
  - Tipo (ex: CAL 0, BAIXO, MÉDIO, ALTO, Teste de Preparo, etc.)
  - PS (parâmetro configurável)
  - Data de preparo (auto-preenchida com o dia atual)
  - Quantidade de etiquetas (até 20 unidades)
- ✅ **Pré-visualização em tempo real** das etiquetas antes da exportação.  
- ✅ **Inclusão opcional de QR Code** com dados da amostra.  
- ✅ **Exportação automática para Word (.docx)** com layout de tabela e bordas para recorte.  

---

## 🧠 Tecnologias Utilizadas

| Tecnologia | Função |
|-------------|--------|
| **HTML5 / CSS3 / JavaScript** | Estrutura e lógica da aplicação |
| **Bootstrap 5** | Layout moderno e responsivo |
| **SweetAlert2** | Modais e alertas elegantes |
| **QRCode Generator** | Criação dos QR Codes locais |
| **docx.js** | Geração de arquivos `.docx` diretamente no navegador |
| **FileSaver.js** | Download automático dos arquivos Word |

---

## 🚀 Como Utilizar

1. Abra o arquivo `index.html` no navegador.  
2. Preencha o formulário com os dados da etiqueta.  
3. Clique em **“Visualizar Etiquetas”** para ver o preview.  
4. Clique em **“Gerar Documento Word”** para baixar o arquivo `.docx`.  

O sistema criará um arquivo chamado **`etiquetas_preparo.docx`**, contendo todas as etiquetas formatadas (4 por linha), prontas para impressão.

---

## 📦 Estrutura do Projeto

---

## 🧩 Demonstração Visual

*()*

---

## 🧑‍💻 Autor

**Raphael Laurentino**  
Desenvolvedor Front-End  
📍 São Paulo - SP  
🔗 [Instagram @raphael.laurentinowski92](https://instagram.com/raphael.laurentinowski92)

---

## 🪪 Licença

Este projeto é de uso livre para fins educacionais e profissionais.  
Sinta-se à vontade para aprimorar e compartilhar! 🤘
