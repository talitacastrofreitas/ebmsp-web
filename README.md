# 🏫 Site Institucional - Escola Bahiana de Medicina e Saúde Pública
Um portal web institucional estático desenvolvido para a **Escola Bahiana de Medicina e Saúde Pública (EBMSP)**. O projeto serve como um modelo conceitual informativo sobre a história, a estrutura acadêmica e os canais de contato da instituição.

---
## 🎯 Seções & Recursos
- **Cabeçalho Principal:** Apresentação do logotipo da Bahiana e uma barra de pesquisa integrada.
- **Menu de Navegação:** Links estruturados para as áreas do site (*Home*, *Cursos*, *Inscrições*, *Orçamentos* e *Contato*), além de botões sociais com efeitos visuais personalizados ao passar o mouse (Facebook, Twitter e Google).
- **Seção Principal (História & Fundação):** Texto completo sobre a fundação da instituição em 1952, a história de idealização liderada pelos médicos pioneiros, transferência de atividades práticas no Hospital Santa Izabel e a grade de graduação atual (Medicina, Biomedicina, Enfermagem, Fisioterapia, Odontologia, Psicologia e Educação Física).
- **Barra Lateral (Sidebar):**
  - Informações de endereço físico da unidade acadêmica de Brotas (Salvador/BA).
  - Mapa interativo embutido diretamente do Google Maps (Iframe).
  - Lista de contatos rápidos contendo telefone convencional, WhatsApp e e-mail.
- **Newsletter:** Formulário integrado para captação de novos e-mails interessados em receber notícias e ofertas de cursos de extensão.
- **Rodapé:** Direitos autorais institucionais.
---
## 📂 Estrutura do Projeto
```bash
Site-Bahiana/
├── css/
│   └── style.css         # Reset geral, regras de layout (floats/grids), cores institucionais e tipografia
├── img/
│   ├── login1.jpg        # Imagem institucional de visualização do campus
│   └── logo.png          # Logotipo oficial da Escola Bahiana
├── index.html            # Estrutura semântica do portal e integração de dependências
└── README.md             # Documentação do projeto
```
---
## 🛠️ Tecnologias Utilizadas
- **HTML5:** Estruturação semântica do site utilizando tags como `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<section>` e `<footer>`.
- **CSS3 (Vanilla):** Estilização de layout com posicionamento fluído via floats, efeitos de transição de cor em links sociais e estilização customizada de formulários.
- **FontAwesome 4.5.0:** Biblioteca de ícones vetoriais usada no menu e na sidebar.
- **Google Fonts (Open Sans):** Tipografia padrão integrada para leitura limpa e confortável.
---
## 💻 Como Rodar o Projeto
Como este projeto utiliza apenas tecnologias estáticas de front-end, você não precisa de um servidor local para rodar.
1. Baixe ou clone o repositório em sua máquina.
2. Dê um clique duplo sobre o arquivo `index.html` para abri-lo diretamente no seu navegador de preferência.
3. Certifique-se de estar conectado à internet, pois a biblioteca FontAwesome e a fonte Open Sans são carregadas via CDNs (links externos).
