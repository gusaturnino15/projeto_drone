Projeto prático da unidade curricular do SESI CE399 , do curso Técnico em
Desenvolvimento de Sistemas — SESI/SENAI Itapeva.


---

## 📌 Informações do Projeto

| Campo | Detalhes |
| :--- | :--- |
| **Autor** | Gustavo Saturnino de Camargo Oliveira |
| **Turma** | 2°B |
| **Professor** | Rafael Ribas |
| **Data** | 17/08/2026 |

---



Landing page de apresentação do , um drone agrícola fictício voltado à
pulverização e ao monitoramento de lavouras. O objetivo da página é convencer o
agricultor a agendar uma demonstração do produto.

O layout foi construído a partir de um protótipo no Figma, com HTML semântico e CSS,
sem frameworks.

Landing page do AgroVant, um drone agrícola fictício para monitoramento e aplicação de defensivos. Desenvolvi o projeto com HTML e CSS seguindo um protótipo do Figma, sendo a responsividade uma das partes mais difíceis.


```
landing-page-drone/
├── index.html        página principal
├── README.md         este arquivo
├── css/
│   └── style.css     estilos do projeto
└── img/              imagens e vídeos
```



- [X] Menu (cabeçalho)
- [X] Hero section
- [X] Especificações
- [X] Vídeo do produto
- [X] Cards de benefícios
- [X] Depoimentos
- [X] Formulário de contato



-  — `header`, `main`, `section`, `footer`
-  com variáveis em `:root`
-  para os layouts
-  com abordagem  e media queries
-  (`rem`, `%`) no lugar de medidas fixas



A página foi construída começando pelo celular. O CSS base atende telas pequenas e as
media queries acrescentam o comportamento das telas maiores, a partir de .

| Tela | Comportamento |
|---|---|
| Celular | O menu de navegação é reduzido, mantendo o botão de agendamento; os cards ficam empilhados; o formulário ocupa praticamente toda a largura da tela; os textos e imagens são reduzidos para melhor adaptação. |
| Desktop | O menu completo é exibido; os cards de especificações são organizados em três colunas; a seção de depoimentos fica distribuída horizontalmente; o formulário e o conteúdo de agendamento aparecem lado a lado. |



```bash
git clone https://github.com/gusaturnino15/projeto_drone.git
cd projeto_drone
```

Depois é só abrir o `index.html` no navegador.



- Protótipo do layout: material da disciplina
- Imagens e vídeos: material fornecido pelo professor
- Fontes: [Roboto](https://fonts.google.com/specimen/Roboto) e
  [Inter](https://fonts.google.com/specimen/Inter), via Google Fonts

---

Projeto acadêmico, sem fins comerciais. O drone AGROVANT é fictício.