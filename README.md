<img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:1e3a8a,50:2563eb,100:7c3aed&text=Giovanni%20Dassi&fontColor=ffffff&fontSize=54&fontAlign=50&fontAlignY=36&desc=Front-end%20%C2%B7%20Produto%20%C2%B7%20IA&descAlign=50&descAlignY=58&descSize=17&animation=fadeIn" width="100%">

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1100&color=6EA8FE&center=true&vCenter=true&width=620&height=58&lines=Construo%20aplica%C3%A7%C3%B5es%20web%20de%20ponta%20a%20ponta%3BReact%20%C2%B7%20Next.js%20%C2%B7%20TypeScript%20%C2%B7%20Supabase%3BIA%20como%20multiplicador%2C%20n%C3%A3o%20como%20muleta%3BDo%20primeiro%20commit%20ao%20deploy%20em%20produ%C3%A7%C3%A3o" alt="O que eu faço">

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-giovanni--dassi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-dassi) [![E-mail](https://img.shields.io/badge/E--mail-contato-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:giovannidassi@gmail.com) [![WhatsApp](https://img.shields.io/badge/WhatsApp-(15)_99681--0270-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5515996810270)

<img src="https://komarev.com/ghpvc/?username=giovannicdbusiness&label=Visitas%20no%20perfil&color=2563eb&style=flat-square" alt="visitas">

</div>

---

## Sobre

Desenvolvedor front-end, 26 anos, interior de São Paulo. Trabalho remoto.

Meu diferencial não é decorar sintaxe: é **entregar produto inteiro sozinho**. Pego um
briefing vago, transformo em escopo, desenho a interface, escrevo o código, modelo o
banco, subo em produção e continuo dando manutenção. Uso IA de forma pesada e deliberada
para acelerar isso, e sou aberto sobre o assunto, porque o mérito não está na digitação:
está em saber **o que** construir, **por que** aquela decisão, e em revisar cada linha
antes dela ir pro ar.

O que me define de verdade é ser detalhista. O espaçamento errado me incomoda, o estado
de loading que ninguém pensou me incomoda, o formulário que não diz o que deu errado me
incomoda. É o que faz meus projetos parecerem caros.

**Atualmente:** desenvolvedor front-end na Lasy AI (remoto), com mais de 20 aplicações em
produção, e tocando projetos próprios de web e produto.

---

## Stack

<div align="center">

[![Stack](https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,supabase,postgres,nodejs,vercel,git,flutter,vite,cloudflare&theme=dark&perline=12)](https://skillicons.dev)

</div>

<table>
<tr>
<td><b>Front-end</b></td>
<td>React 19, Next.js (App Router, Server Actions), TypeScript strict, Tailwind, shadcn/ui, Radix, Framer Motion</td>
</tr>
<tr>
<td><b>Back-end e dados</b></td>
<td>Supabase (Postgres, Auth, RLS, RPC), migrations versionadas, Cloudflare R2, edge functions</td>
</tr>
<tr>
<td><b>Produto</b></td>
<td>Escopo a partir do briefing, arquitetura de informação, UX de conversão, copy que vende</td>
</tr>
<tr>
<td><b>IA aplicada</b></td>
<td>Claude Code, Cursor, Vercel AI SDK, Gemini. Copilotos e insights dentro do produto, não só na escrita do código</td>
</tr>
<tr>
<td><b>Infra</b></td>
<td>Vercel, cron jobs, Web Push VAPID, Playwright, CI de build</td>
</tr>
</table>

---

## Projetos em destaque

### ⚽ [Bolão da Galera](https://github.com/giovannicdbusiness/bolao-app)

> PWA full-stack de bolão esportivo. Em produção, com wrapper nativo para Android e iOS.

<a href="https://github.com/giovannicdbusiness/bolao-app">
<img src="assets/bolao-banner.png" width="100%" alt="Bolão da Galera">
</a>

Grupos privados, palpites em jogos reais, ranking ao vivo e push. A parte difícil não é a
tela: é garantir que ninguém palpite depois do apito inicial (validado por RLS no
Postgres, não no front), que a pontuação seja idêntica pra todo mundo (engine pura com 18
testes que rodam antes de cada build) e que o cron de 5 em 5 minutos não mande a mesma
notificação duas vezes.

`Next.js 16` `React 19` `TypeScript strict, zero any` `Supabase + RLS` `27 migrations` `Web Push VAPID` `5 cron jobs` `Flutter`

**[▶ bolaodagalera.pro](https://www.bolaodagalera.pro)**

<br>

### 🏥 [Rede Evolução](https://github.com/giovannicdbusiness/clinica-evolucao-site)

> Site de conversão para rede de clínicas de reabilitação. **Cliente real.**

<a href="https://github.com/giovannicdbusiness/clinica-evolucao-site">
<img src="assets/clinica.png" width="100%" alt="Rede Evolução">
</a>

Quem chega nesse site quase nunca é o paciente: é a mãe, a esposa, o irmão, em crise, no
celular. Isso definiu tudo. O formulário de triagem não manda e-mail pra uma caixa que
alguém abre na segunda: monta a mensagem e abre o WhatsApp da unidade certa já
preenchido. Cinco marcas (a rede e as 4 unidades) rodam na mesma base de código, cada uma
com tema, galeria, FAQ e telefone próprios.

`React 19` `TypeScript` `Vite` `Tailwind 4` `Framer Motion` `edge function`

**[▶ clinicaredeevolucao.com.br](https://www.clinicaredeevolucao.com.br)**

<br>

### 🍽️ [Sabor & Cia](https://github.com/giovannicdbusiness/sabor-vision)

> Painel operacional multi-tenant para uma rede de dark kitchens.

<a href="https://github.com/giovannicdbusiness/sabor-vision">
<img src="assets/sabor.png" width="100%" alt="Sabor e Cia">
</a>

Dois perfis, duas visões, os mesmos dados protegidos por RLS no banco: o gestor vê a rede
inteira, o gerente vê só a unidade dele. Metas, pedidos, cancelamentos, ranking e insights
escritos por IA. Nasceu de um teste técnico e virou produto.

`TanStack Start` `React Query` `Supabase + RLS` `Recharts` `Gemini`

**[▶ ver o painel](https://sabor-e-cia-eight.vercel.app)** (credenciais de demo no README do projeto)

<br>

### 📦 [ML Command Center](https://github.com/giovannicdbusiness/ml-command-center)

> CRM analítico AI-native para sellers do Mercado Livre.

<a href="https://github.com/giovannicdbusiness/ml-command-center">
<img src="assets/ml.png" width="100%" alt="ML Command Center">
</a>

O painel do Mercado Livre responde "quanto vendi?". Ninguém perde dinheiro por não saber
isso. Perde por romper o estoque com lead time de 75 dias, por ver a margem evaporar no
câmbio e por perder o Buy Box sem notar. Cada tela aqui termina numa ação com prazo e
valor em reais.

`Next.js 15` `Recharts` `Vercel AI SDK` `Gemini 2.5 Flash` `seed determinística`

**[▶ ver a demo](https://app-ml-two.vercel.app/login)**

---

## Atividade

<div align="center">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=giovannicdbusiness&bg_color=0d1117&color=6EA8FE&line=7c3aed&point=ffffff&area=true&hide_border=true&custom_title=Contribuicoes%20recentes" alt="Grafico de contribuicoes">

<img width="98%" src="https://raw.githubusercontent.com/giovannicdbusiness/giovannicdbusiness/output/snake-dark.svg" alt="Snake das contribuicoes">

<sub>A maior parte do meu trabalho vive em repositórios privados de clientes e produto.<br>
Os quatro projetos acima são o que eu posso mostrar por inteiro, código e tudo.</sub>

</div>

---

<div align="center">

### Aberto a oportunidades

Vagas remotas de front-end e projetos freelance de web e produto.

[![LinkedIn](https://img.shields.io/badge/Chamar_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-dassi) [![WhatsApp](https://img.shields.io/badge/Chamar_no_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5515996810270)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:7c3aed,50:2563eb,100:1e3a8a" width="100%">
