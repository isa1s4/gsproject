📘 FutureConnect – Plataforma de Talentos

Plataforma web interativa criada para conectar talentos às demandas do futuro do trabalho. O projeto apresenta perfis profissionais dinâmicos, modal com detalhes completos, e um quiz interativo sobre tendências do mercado.

🚀 Funcionalidades Principais
🔹 1. Exibição de perfis profissionais

Cards responsivos gerados dinamicamente com JavaScript.

Exibe foto, nome, cargo e skills principais.

Animações no hover (elevação + destaque).

🔹 2. Modal detalhado (Slideshow com Abas)

Ao clicar em um card, abre-se um modal com:

Foto ampliada

Cargo, resumo pessoal e detalhes completos

Abas com:

Experiências & Skills Técnicas

Formação Acadêmica

Soft Skills & Hobbies

Totalmente animado com transições suaves.

🔹 3. Quiz interativo sobre Futuro do Trabalho

Inclui:

Perguntas de múltipla escolha

Feedback de resposta correta ou incorreta

Controle de fluxo (próxima pergunta automático)

🔹 4. Interface moderna e responsiva

Construída com:

Tailwind CSS (via CDN)

Fontes Inter

Cores personalizadas

Layout mobile-first

🛠️ Tecnologias Utilizadas
Tecnologia	Função
HTML5	Estrutura da aplicação
CSS + Tailwind	Estilização e responsividade
JavaScript Vanilla	Dinâmica dos cards, modal e quiz
Placehold.co	Imagens temporárias para perfis
📂 Estrutura de Pastas (sugerida)
/projeto
 ├── index.html
 ├── /images
 │     ├── logo.png
 │     └── logo1.png
 └── README.md


Obs.: Certifique-se de que as imagens logo.png e logo1.png estejam na pasta correta.

▶️ Como Executar o Projeto

Baixe ou clone o repositório:

git clone https://github.com/seuusuario/nome-do-repo.git


Abra o arquivo index.html no navegador.
Não é necessário servidor local.

📌 Pontos Importantes

✔ O projeto não usa frameworks JavaScript, tudo é feito com JavaScript puro.
✔ O modal usa animações CSS (fade + bounce).
✔ A grid de cards se adapta a 1, 2 ou 3 colunas, dependendo do tamanho da tela.
✔ Os dados dos perfis estão em um array chamado PROFISSIONAIS_DATA, podendo ser substituídos por dados reais.

🧩 Como adicionar novos perfis

Dentro do JavaScript, adicione um novo objeto ao array:

{
  id: 4,
  nome: "Novo Nome",
  cargo: "Nova Profissão",
  foto: "url-da-foto",
  skills_basicas: ["HTML", "CSS", "JS"],
  pessoal: "Resumo pessoal...",
  academico: ["Formação 1", "Formação 2"],
  experiencia: ["Experiência 1", "Experiência 2"],
  soft_skills: ["Comunicação", "Liderança"],
  hobbies: ["Leitura", "Tecnologia"]
}

❗ Possíveis Melhorias Futuras

 Adicionar backend com Node.js

 Persistir dados dos perfis via API

 Dashboard para administrar profissionais

 Sistema de login para recrutadores

 Exportar perfil em PDF


  Link para a pagina online pelo GitHub: https://isa1s4.github.io/gsproject/
  Link do repositório: https://github.com/isa1s4/gsproject

 🧑‍💻 Autor

Desenvolvido por Isabela Vitória (RM 559255) como parte da GLOBAL SOLUTION da FIAP, integrando as disciplinas:

Web Development – Prof. Wellington Cidade

Frontend Design – Prof. Lucas Sousa


Gostaria de adicionar uma nota final para os professores que considerem o fato de que eu tive pouco tempo para fazer e um boa parte de codigo eu tive que corrigir no trem porque estou  trabalhando direto e não tive muito tempo, tanto é que estou enviado as 4H da manhã porque cheguei a 00H e vim correndo terminar. depois que for avaiado eu vou tirar essa nota para poder corrigir o que for nescessario e subir para o linkedin, obrigado pela atenção e paciencia.

 Tema dark/light
 
