# Rocky Tree Technologies - Soluções em TI, Infraestrutura & Web

<div align="center">
  <h3><strong>Soluções Sólidas em Tecnologia.</strong></h3>
  <p>Do hardware à web. Engenharia de hardware, infraestrutura corporativa de redes, desenvolvimento web sob medida e suporte técnico especializado.</p>
</div>

<br>

## Sobre o Projeto

Presença digital oficial da **Rocky Tree Technologies**. Desenvolvido sob a arquitetura **One Page (Single Page)** de rolagem contínua com elementos de **Landing Page de Alta Conversão**, o projeto equilibra soluções completas de tecnologia corporativa: **engenharia de hardware, manutenção técnica presencial em Santo Antônio de Jesus (SAJ) e região**, infraestrutura corporativa e suporte remoto com desenvolvimento web para empresas em todo o Brasil.

---

## Identidade Visual e Experiência Interativa (UI/UX)

- **Design Tecnológico Moderno & Fluido:** Fundo com padrão de grade sutil e **Spotlight interativo dinâmico** que rastreia suavemente a posição do cursor na tela, além de orbes de iluminação ambiente.
- **Efeito de Digitação no Título Principal:** Animação precisa de digitação automática no carregamento para "Soluções Sólidas em Tecnologia." com realce gradiente neon.
- **Acentos em Verde-Limão Elétrico (`#ccff00`):** Aplicação equilibrada em botões de ação (CTAs), destaques interativos e indicadores de status em tempo real.
- **Ícones SVG Minimalistas:** Substituição completa de emojis por ícones vetoriais lineares de alta precisão e acabamento profissional.
- **Interatividade Humana e Funcional:** 
  - **Simulador Rápido de Atendimento:** Permite ao visitante selecionar as soluções necessárias e gerar um pedido formatado instantâneo para o WhatsApp.
  - **Filtro Dinâmico de Portfólio:** Navegação fluida por categorias (Sites para Empresas, Hardware & Suporte, Redes Corporativas, Identidade Visual).
  - **FAQ Interativo em Accordion:** Esclarecimento de dúvidas frequentes em linguagem clara e acessível, sem jargões desnecessários.
  - **Spotlight Magnético nos Cards:** Efeito de iluminação radial dinâmica (`--mouse-x`, `--mouse-y`) ao passar o mouse sobre os blocos.
  - **Feedback Táctil:** Animação de onda suave (ripple effect) ao clicar em botões.

---

## Estrutura One Page

1. **Hero & Proposta de Valor:** Título com efeito de digitação suave, slogan minimalista de alto impacto, métricas animadas e botões diretos de conversão.
2. **Sobre Nós:** Apresentação da empresa conduzida por **técnicos especializados**, detalhando o Laboratório & Hardware (presencial regional) e a Divisão Digital & Remota para todo o país.
3. **Soluções Especializadas:** 4 blocos de serviços com 8 tags acessíveis cada (total de 32 tags), com modal detalhado de valores claros ("A consultar" para sites e R$ 150 a R$ 250/mês para suporte web).
4. **Simulador de Serviços:** Ferramenta interativa com ícones SVG modernos para seleção e orçamento com 1 clique para WhatsApp.
5. **Cases & Projetos:** Vitrine de projetos com filtros por categoria e botão de contato contextualizado.
6. **Modelos de Atendimento:** Comparativo claro entre Projetos Avulsos (demandas sob medida / a consultar) e Assinaturas Mensais com atendimento prioritário.
7. **Dúvidas Frequentes (FAQ):** Accordions com explicações simples para quem não tem conhecimento técnico avançado.
8. **Contato & Atendimento:** Informações oficiais e formulário express que conecta o visitante diretamente com os técnicos especializados no WhatsApp: **(75) 99872-9593**.

---

## TreeBot IA 3.0 & Arquitetura Segura da API (Groq)

Para preservar o **sigilo absoluto** da chave de API `GROQ_API_KEY` (evitando exposição no navegador e vazamento em repositórios públicos):

1. **Sigilo de Credenciais (Vercel Serverless Function):**
   - O projeto utiliza a função backend [`api/chat.js`](api/chat.js) nativa da Vercel.
   - A `GROQ_API_KEY` é configurada nas **Environment Variables** da Vercel, mantendo a chave 100% no servidor sem qualquer exposição no navegador.
2. **Motor Resiliente Local (Fail-Safe Instantâneo):**
   - Caso o backend esteja offline ou em configuração, o `treebot.js` possui um motor de resolução de intenções local integrado. Ele responde instantaneamente em linguagem acessível a dúvidas sobre preços (valores a consultar para sites e planos mensais de suporte), serviços de hardware e direciona o usuário para os técnicos especializados via WhatsApp oficial.

---

## Equipe Técnica Especializada

- **Laboratório & Hardware:** Diagnóstico avançado em bancada, reparos eletrônicos de placas, troca de peças, conserto e suporte presencial na região de Santo Antônio de Jesus e cidades vizinhas.
- **Infraestrutura, Redes & Web:** Cabeamento estruturado, roteamento empresarial, segurança de rede, Wi-Fi estável e desenvolvimento web moderno sob medida para todo o país.

---

<div align="center">
  <p>Construído por <strong>Rocky Tree Technologies</strong> &copy; 2026.</p>
</div>
