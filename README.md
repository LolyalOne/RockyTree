# 🌳 Rocky Tree Technologies - Soluções em Tecnologia & Manutenção em SAJ

<div align="center">
  <h3><strong>Soluções Sólidas em Tecnologia.</strong></h3>
  <p>Do hardware à web. Manutenção especializada em Santo Antônio de Jesus (SAJ), Infraestrutura de Redes e Criação de Sites para Empresas.</p>
</div>

<br>

## 🚀 Sobre o Projeto

Presença digital oficial da **Rocky Tree Technologies**. Desenvolvido sob a arquitetura **One Page (Single Page)** de rolagem contínua com elementos de **Landing Page de Alta Conversão**, o projeto tem foco prioritário em **manutenção técnica presencial em Santo Antônio de Jesus (SAJ)** e atendimento remoto de suporte e desenvolvimento web para todo o Brasil.

---

## 🎨 Identidade Visual e Experiência Interativa (UI/UX)

- **Design Tecnológico Moderno & Fluido:** Fundo com padrão de grade sutil e **Spotlight interativo dinâmico** que rastreia suavemente a posição do cursor na tela, além de orbes de iluminação ambiente.
- **Acentos em Verde-Limão Elétrico (`#ccff00`):** Aplicação equilibrada em botões de ação (CTAs), destaques interativos e indicadores de status em tempo real.
- **Interatividade Humana e Funcional:** 
  - **Simulador Rápido de Atendimento:** Permite ao visitante selecionar as soluções necessárias e gerar um pedido formatado instantâneo para o WhatsApp.
  - **Filtro Dinâmico de Portfólio:** Navegação fluida por categorias (Sites para Empresas, Manutenção em SAJ, Redes Corporativas, Identidade Visual).
  - **FAQ Interativo em Accordion:** Esclarecimento de dúvidas frequentes em linguagem clara e acessível, sem jargões desnecessários.
  - **Spotlight Magnético nos Cards:** Efeito de iluminação radial dinâmica (`--mouse-x`, `--mouse-y`) ao passar o mouse sobre os blocos.
  - **Feedback Táctil:** Animação de onda suave (ripple effect) ao clicar em botões.

---

## ✨ Estrutura One Page

1. **Hero & Proposta de Valor:** Título sólido de alto impacto, slogan minimalista sem redundâncias, métricas animadas e botões diretos de conversão.
2. **Sobre Nós:** Apresentação da empresa conduzida por **técnicos especializados**, detalhando a Divisão Presencial em SAJ e a Divisão Digital & Remota para todo o país.
3. **Soluções Especializadas:** 4 blocos de serviços com 8 tags acessíveis cada (total de 32 tags), com modal detalhado de valores claros ("A consultar" para sites e R$ 150 a R$ 250/mês para suporte web).
4. **Simulador de Serviços:** Ferramenta interativa para seleção e orçamento com 1 clique para WhatsApp.
5. **Cases & Projetos:** Vitrine de projetos com filtros por categoria, sem poluição de métricas no canto e com botão de contato contextualizado.
6. **Modelos de Atendimento:** Comparativo claro entre Projetos Avulsos (demandas sob medida / a consultar) e Assinaturas Mensais com atendimento prioritário.
7. **Dúvidas Frequentes (FAQ):** Accordions com explicações simples para quem não tem conhecimento técnico avançado.
8. **Contato & Atendimento:** Informações oficiais e formulário express que conecta o visitante diretamente com os técnicos especializados no WhatsApp: **(75) 99872-9593**.

---

## 🤖 TreeBot IA 3.0 & Arquitetura Segura da API (Groq)

Para preservar o **sigilo absoluto** da chave de API `GROQ_API_KEY` (evitando exposição no navegador e vazamento em repositórios públicos):

1. **Sigilo de Credenciais (Vercel Serverless Function):**
   - O projeto utiliza a função backend [`api/chat.js`](api/chat.js) nativa da Vercel.
   - A `GROQ_API_KEY` é configurada nas **Environment Variables** da Vercel, mantendo a chave 100% no servidor sem qualquer exposição no navegador.
2. **Motor Resiliente Local (Fail-Safe Instantâneo):**
   - Caso o backend esteja offline ou em configuração, o `treebot.js` possui um motor de resolução de intenções local integrado. Ele responde instantaneamente em linguagem acessível a dúvidas sobre preços (valores a consultar para sites e planos mensais de suporte), manutenção em SAJ e direciona o usuário para os técnicos especializados via WhatsApp oficial.

---

## 👥 Equipe Técnica Especializada

- **Manutenção & Hardware em SAJ:** Diagnóstico avançado em bancada, reparos eletrônicos de placas, troca de peças, conserto e suporte presencial na região de Santo Antônio de Jesus.
- **Infraestrutura, Redes & Web:** Cabeamento estruturado, roteamento empresarial, segurança de rede, Wi-Fi estável e desenvolvimento web moderno sob medida.

---

<div align="center">
  <p>Construído por <strong>Rocky Tree Technologies</strong> &copy; 2026.</p>
</div>
