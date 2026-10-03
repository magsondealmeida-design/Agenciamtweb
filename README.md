# MT Web Agency Hub

CRIAÇÃO DO SAAS — AGÊNCIA MT WEB

1. VISÃO GERAL DO PROJETO

Crie uma plataforma SaaS completa chamada Agência MT Web, uma agência digital automatizada que permite a representantes e afiliados venderem serviços de tecnologia e marketing digital para empresas.

A plataforma deverá funcionar como um ecossistema de negócios digitais, no qual cada representante terá sua própria área de trabalho para prospectar empresas, cadastrar clientes, vender serviços, acompanhar projetos, controlar receitas e utilizar ferramentas de criação de sites e conteúdo.

O proprietário da plataforma terá uma área administrativa central para controlar assinaturas mensais, representantes, afiliados, cursos, serviços e toda a operação do sistema.

O objetivo é criar uma solução profissional, escalável, responsiva e de baixo custo operacional, priorizando o uso eficiente dos créditos disponíveis no Emergent.

2. PRINCÍPIOS DE DESENVOLVIMENTO — ECONOMIA DE CRÉDITOS

Antes de desenvolver, siga estas regras:

Construa primeiro um MVP funcional, sem desperdiçar créditos em recursos avançados que não são essenciais para o lançamento.

Utilize componentes reutilizáveis, banco de dados estruturado e arquitetura modular.

Não gere dezenas de páginas duplicadas ou códigos desnecessários.

Não utilize serviços pagos externos sem necessidade.

Priorize ferramentas gratuitas, APIs gratuitas quando disponíveis e integrações que possam ser configuradas posteriormente.

Não invente integrações funcionando quando elas exigem credenciais ou APIs que ainda não foram configuradas.

Recursos avançados devem ter uma implementação inicial simples, com possibilidade de evolução.

Não construa um clone completo de plataformas como HubSpot, Canva ou Semrush nesta primeira versão.

Desenvolva o sistema em etapas, mantendo o que já estiver funcionando.

Antes de implementar funcionalidades que consumam muitos créditos, priorize as telas, o banco de dados e os fluxos principais de negócio.

Se houver limitações técnicas ou de orçamento, entregue primeiro a versão funcional do núcleo do SaaS e deixe os recursos avançados preparados para integração futura.

3. IDENTIDADE VISUAL

Nome: Agência MT Web

Slogan sugerido: Sua agência digital. Seu negócio. Seu crescimento.

Estilo visual:

Moderno e profissional.

Aparência de plataforma SaaS premium.

Interface limpa, intuitiva e responsiva.

Cores principais: azul, verde e branco, com tons neutros.

Tipografia moderna.

Dashboard com cards, gráficos, tabelas e indicadores.

Compatibilidade com computador, tablet e celular.

Modo claro como padrão, com possibilidade de modo escuro futuramente.

O sistema deve transmitir tecnologia, oportunidade de negócio, automação, confiança e crescimento financeiro.

4. PERFIS DE USUÁRIOS E PERMISSÕES

4.1 Administrador Master

O administrador é o proprietário da Agência MT Web.

Permissões:

Controle total da plataforma.

Gestão de representantes.

Gestão de afiliados.

Gestão de assinaturas e planos.

Gestão financeira geral.

Gestão de cursos e treinamentos.

Gestão dos serviços oferecidos.

Gestão de templates.

Gestão de comissões.

Configuração das integrações.

Relatórios gerais.

Controle de acesso e permissões.

4.2 Representante

O representante é um parceiro comercial que paga uma assinatura mensal para utilizar o ecossistema.

Permissões:

Acessar seu dashboard.

Cadastrar e gerenciar seus clientes.

Prospectar empresas.

Criar propostas comerciais.

Vender serviços.

Acompanhar projetos.

Controlar receitas, despesas e comissões.

Utilizar ferramentas de criação de sites e landing pages.

Gerar conteúdos para redes sociais.

Acessar cursos e treinamentos.

Divulgar o ecossistema como afiliado, se habilitado.

Cada representante deve visualizar somente seus próprios clientes, vendas, projetos, dados financeiros e comissões, salvo permissões administrativas específicas.

4.3 Afiliado

O afiliado poderá divulgar a Agência MT Web e receber comissões por assinaturas qualificadas.

Funcionalidades:

Cadastro e login.

Link ou código de indicação exclusivo.

Dashboard de cliques, leads, conversões e comissões.

Histórico de indicações.

Status das assinaturas indicadas.

Regras de comissão configuráveis pelo administrador.

Solicitação de pagamento de comissões.

Materiais de divulgação.

O sistema deverá distinguir afiliados comuns de representantes que também participam do programa de afiliados.

5. ESTRUTURA PRINCIPAL DO SISTEMA

Crie uma aplicação SaaS com as seguintes áreas:

Landing page pública.

Cadastro e login.

Dashboard do representante.

CRM e gestão de clientes.

Prospecção de empresas.

Catálogo de serviços.

Orçamentos e propostas.

Gestão de projetos.

Gerador de sites e landing pages.

Gerador de conteúdos para redes sociais.

Calendário de conteúdo.

Controle financeiro.

Cursos e treinamentos.

Programa de afiliados.

Dashboard administrativo.

Gestão de assinaturas.

Configurações e integrações.

6. LANDING PAGE PÚBLICA

Crie uma página de apresentação da Agência MT Web com foco em atrair representantes e afiliados.

Seções:

Hero com título impactante.

Explicação sobre o ecossistema.

Benefícios para representantes.

Serviços que podem ser vendidos.

Como funciona em 3 ou 4 etapas.

Ferramentas disponíveis.

Cursos e capacitação.

Planos de assinatura.

Programa de afiliados.

Perguntas frequentes.

Chamada para cadastro.

CTAs:

Quero ser representante.

Conhecer os planos.

Quero ser afiliado.

Entrar na plataforma.

A página deve ser otimizada para conversão, com boa experiência mobile e estrutura preparada para SEO.

7. AUTENTICAÇÃO E ASSINATURAS

Implemente:

Cadastro de usuário.

Login.

Recuperação de senha.

Verificação de e-mail, quando disponível.

Perfis e permissões.

Controle de sessão.

Status da assinatura.

Planos configuráveis pelo administrador:

Nome do plano.

Preço mensal.

Limite de clientes.

Limite de projetos.

Limite de geração de conteúdo.

Recursos disponíveis.

Status ativo ou inativo.

O administrador deverá poder criar, editar e desativar planos.

O sistema deverá suportar cobrança recorrente mensal, mas a integração de pagamento deverá ser implementada somente quando houver credenciais e provedor configurados. Não simule pagamentos reais.

Enquanto a integração não estiver disponível, permita o gerenciamento manual de assinaturas pelo administrador e deixe a arquitetura preparada para gateway de pagamento.

8. DASHBOARD DO REPRESENTANTE

Crie um painel central com:

Saudação personalizada.

Plano atual.

Status da assinatura.

Quantidade de clientes.

Projetos ativos.

Propostas enviadas.

Vendas realizadas.

Receita do mês.

Comissões previstas.

Contas a receber.

Atividades recentes.

Atalhos para criar site, prospectar e gerar conteúdo.

Avisos e notificações.

Exiba gráficos simples:

Evolução das vendas.

Receita mensal.

Clientes conquistados.

Projetos por status.

Use dados reais do banco de dados do usuário autenticado.

9. CRM E GESTÃO DE CLIENTES

Crie um CRM completo e simples para o representante controlar seus clientes.

Cadastro:

Nome da empresa.

Nome do responsável.

Telefone.

E-mail.

Cidade e estado.

Segmento de negócio.

CNPJ, opcional.

Site atual, se houver.

Redes sociais.

Observações.

Origem do lead.

Status do relacionamento.

Funil de vendas:

Novo lead.

Contato realizado.

Reunião agendada.

Proposta enviada.

Negociação.

Cliente ganho.

Cliente perdido.

Funcionalidades:

Busca e filtros.

Cadastro de contatos.

Histórico de interações.

Tarefas e lembretes.

Anotações.

Conversão de lead em cliente.

Vinculação de projetos e propostas.

Isolamento obrigatório: um representante não pode acessar os clientes de outro representante.

10. PROSPECÇÃO AUTOMATIZADA DE EMPRESAS

Crie um módulo chamado Radar de Oportunidades.

Objetivo: ajudar o representante a encontrar empresas que possuem pouca ou nenhuma presença digital.

Filtros:

Cidade.

Estado.

Segmento.

Empresas sem site.

Empresas sem redes sociais identificadas.

Empresas com presença digital incompleta.

Empresas com dados de contato disponíveis.

Cada oportunidade deverá apresentar:

Nome da empresa.

Segmento.

Cidade.

Telefone, quando obtido legalmente.

Site, se existir.

Redes sociais encontradas.

Indicadores de presença digital.

Data da pesquisa.

Status da prospecção.

Botão para adicionar ao CRM.

A pesquisa deverá ser implementada por meio de fontes e APIs autorizadas, respeitando termos de uso, privacidade e limites de requisições.

Não realize scraping indiscriminado de mecanismos de busca, não burle CAPTCHAs e não invente empresas ou contatos.

Na primeira versão, se não houver API de pesquisa disponível, crie:

Interface de filtros.

Cadastro manual de oportunidades.

Importação de dados por CSV.

Estrutura de integração futura com APIs de mapas, diretórios e fontes autorizadas.

Crie um sistema de pontuação de oportunidade baseado em critérios verificáveis, como ausência de site identificado ou ausência de informações digitais, sem afirmar que uma empresa não possui presença online quando isso não foi comprovado.

11. CATÁLOGO DE SERVIÇOS

O administrador poderá cadastrar serviços comercializáveis.

Serviços iniciais:

Criação de site institucional.

Criação de landing page.

Loja virtual.

Integração com redes sociais.

Configuração de Google Business Profile.

SEO local.

Criação de conteúdo.

Artes para Instagram e Facebook.

Vídeos curtos para redes sociais.

Automação de atendimento.

Funis de vendas.

Integrações com ferramentas de IA.

Cada serviço terá:

Nome.

Descrição.

Imagem ou ícone.

Preço sugerido.

Prazo estimado.

Categoria.

Status ativo/inativo.

Comissão do representante, quando aplicável.

O representante poderá selecionar serviços e montar uma proposta comercial para seu cliente.

12. ORÇAMENTOS E PROPOSTAS

Crie um gerador de propostas profissionais.

Funcionalidades:

Seleção do cliente.

Seleção de serviços.

Quantidade.

Desconto.

Valor total.

Prazo estimado.

Condições de pagamento.

Observações.

Validade da proposta.

Status: rascunho, enviada, aceita, recusada, expirada.

A proposta deverá ter uma apresentação profissional com a marca Agência MT Web e a identificação do representante.

Permita visualizar e imprimir a proposta. Se a geração de PDF estiver disponível de forma econômica, implemente-a; caso contrário, priorize uma página de impressão otimizada.

Prepare a arquitetura para assinatura eletrônica futura, sem simular assinaturas válidas.

13. GESTÃO DE PROJETOS DOS CLIENTES

Cada venda poderá originar um projeto.

Funcionalidades:

Nome do projeto.

Cliente.

Serviço contratado.

Valor.

Data de início.

Prazo.

Status.

Checklist de tarefas.

Observações.

Arquivos, se suportados.

Histórico de alterações.

Status:

Aguardando início.

Em andamento.

Aguardando cliente.

Em revisão.

Concluído.

Cancelado.

Crie uma visão em lista e uma visão Kanban simples.

O representante deverá controlar o andamento de todos os serviços de seus clientes em um único lugar.

14. CRIADOR DE SITES E LANDING PAGES

Crie um módulo de criação assistida de sites.

Fluxo:

O representante escolhe um cliente.

Informa segmento e objetivo.

Seleciona um template.

Informa nome da empresa, descrição, serviços e contatos.

O sistema gera uma estrutura inicial de conteúdo.

O representante edita os textos e informações.

Visualiza o resultado.

Salva o projeto.

Publica ou exporta conforme as integrações disponíveis.

Templates iniciais:

Site institucional.

Landing page de serviços.

Página de captura de leads.

Página de apresentação de empresa local.

Não é necessário criar um construtor visual complexo no MVP. Priorize:

Templates responsivos.

Campos editáveis.

Preview.

Geração assistida de conteúdo.

Salvamento de projetos.

Estrutura preparada para publicação futura em hospedagem ou domínio personalizado.

Não prometa publicação automática em domínios externos sem uma integração real configurada.

15. GERADOR AUTOMÁTICO DE CONTEÚDO

Crie uma ferramenta para gerar conteúdos de marketing digital para os clientes dos representantes.

Segmentos iniciais:

Energia solar.

Marketing digital.

Saúde e bem-estar.

Renda extra.

Empresas locais.

Serviços profissionais.

O representante deverá informar:

Cliente.

Nicho.

Objetivo.

Rede social.

Tipo de conteúdo.

Tom de voz.

Tema.

Chamada para ação.

Frequência.

Tipos:

Post para Instagram.

Legenda.

Roteiro de Reels.

Carrossel.

Texto para Facebook.

Ideias de Stories.

Artigo para blog.

Anúncio publicitário.

O sistema deverá gerar:

Título.

Texto.

Legenda.

Hashtags relevantes.

CTA.

Sugestão de imagem.

Roteiro, quando aplicável.

Integração com IA:

Crie uma camada de serviço que permita conectar um provedor de IA por API.

Não exponha chaves de API no frontend.

Permita configuração segura pelo administrador.

Caso a API não esteja configurada, ofereça um fluxo manual de criação e edição.

Controle limites de uso por plano para evitar custos inesperados.

Para conteúdo de saúde, não faça promessas médicas, diagnósticos ou afirmações sem base. Para marketing e renda extra, evite promessas de ganhos garantidos.

16. CALENDÁRIO DE CONTEÚDO

Crie um calendário para cada cliente.

Funcionalidades:

Visualização mensal e semanal.

Agendamento de ideias.

Status: ideia, em produção, aprovado, publicado.

Tipo de conteúdo.

Rede social.

Legenda.

Arquivo ou arte, quando disponível.

Responsável.

Observações.

A publicação automática em Instagram, Facebook e outras redes deverá ser feita somente por APIs oficiais e contas autorizadas.

Na primeira versão, implemente:

Calendário.

Organização das publicações.

Botão para copiar conteúdo.

Exportação ou compartilhamento manual.

Estrutura para integrações futuras.

Não afirme que o sistema publicou algo se apenas gerou o conteúdo.

17. CONTROLE FINANCEIRO DO REPRESENTANTE

Crie um módulo financeiro individual por representante.

Funcionalidades:

Receitas.

Despesas.

Contas a receber.

Contas pagas.

Comissões.

Serviços vendidos.

Mensalidades dos clientes.

Categorias financeiras.

Filtros por período.

Relatórios.

Saldo previsto e realizado.

Cada lançamento deverá ter:

Descrição.

Tipo.

Valor.

Data.

Categoria.

Cliente relacionado, opcional.

Projeto relacionado, opcional.

Status.

Observações.

Dashboard financeiro:

Receita bruta.

Despesas.

Resultado estimado.

Valores pendentes.

Comissões.

Evolução mensal.

Importante: separar claramente o faturamento do representante, os valores devidos à Agência MT Web e as comissões. Não considerar receita como lucro sem descontar os custos e obrigações.

18. CURSOS E TREINAMENTOS

Crie uma área de capacitação para representantes e afiliados.

O administrador poderá cadastrar:

Cursos.

Módulos.

Aulas.

Vídeos ou links.

Materiais de apoio.

Questionários simples.

Ordem de apresentação.

Status publicado/rascunho.

Cursos iniciais sugeridos:

Como utilizar a Agência MT Web.

Como prospectar empresas.

Como vender criação de sites.

Como vender landing pages.

Como utilizar o gerador de conteúdo.

Como conquistar clientes locais.

Como organizar o financeiro.

Marketing digital para representantes.

Funcionalidades:

Progresso individual.

Aulas concluídas.

Certificado futuro.

Controle de acesso conforme o plano.

Não hospede vídeos pesados diretamente no sistema se isso aumentar significativamente o custo. Priorize links de vídeos hospedados em plataformas adequadas.

19. PROGRAMA DE AFILIADOS

Crie um sistema de afiliados integrado ao SaaS.

O administrador poderá definir:

Percentual ou valor fixo de comissão.

Produtos ou planos elegíveis.

Prazo de atribuição.

Período de recorrência da comissão.

Regras de cancelamento.

Valor mínimo para saque.

Status de aprovação.

Funcionalidades do afiliado:

Link exclusivo.

Código de indicação.

Dashboard.

Cliques.

Cadastros.

Assinaturas qualificadas.

Comissões pendentes.

Comissões aprovadas.

Comissões pagas.

Solicitação de saque.

Regras:

Não contabilizar comissão duplicada.

Registrar origem da indicação.

Registrar status da assinatura.

Permitir auditoria pelo administrador.

Não liberar comissão de pagamento que ainda não foi confirmado.

Não simular pagamentos reais.

O sistema deverá estar preparado para integração com gateways de pagamento, mas sem depender de um gateway específico no MVP.

20. DASHBOARD ADMINISTRATIVO

Crie uma área exclusiva para o administrador master.

Indicadores:

Total de representantes.

Representantes ativos.

Assinaturas ativas.

Assinaturas pendentes.

Receita recorrente mensal registrada.

Novos cadastros.

Clientes cadastrados.

Projetos em andamento.

Total de afiliados.

Comissões pendentes.

Taxa de conversão, quando houver dados suficientes.

Módulos administrativos:

Usuários.

Representantes.

Afiliados.

Planos.

Assinaturas.

Serviços.

Templates.

Cursos.

Comissões.

Financeiro geral.

Configurações.

Logs e auditoria.

O administrador deverá conseguir pesquisar, filtrar, editar e visualizar registros.

21. MODELO DE DADOS

Estruture o banco de dados com entidades relacionadas:

users

roles

representative_profiles

affiliate_profiles

subscription_plans

subscriptions

clients

leads

lead_activities

services

proposals

proposal_items

projects

project_tasks

websites

website_templates

content_generations

content_calendar

financial_transactions

courses

course_modules

lessons

lesson_progress

affiliate_referrals

commissions

payouts

notifications

audit_logs

integrations

Todos os dados deverão possuir relacionamentos consistentes e controle de propriedade.

Implemente isolamento por usuário/representante no backend, não apenas escondendo dados no frontend.

22. SEGURANÇA

Implemente:

Autenticação segura.

Senhas armazenadas com hash seguro.

Controle de acesso baseado em papéis.

Validação de dados no backend.

Proteção de rotas.

Isolamento de dados entre representantes.

Não exposição de chaves de API.

Logs de ações administrativas.

Proteção contra acesso indevido a registros.

Tratamento de erros sem expor informações sensíveis.

A plataforma deverá respeitar a LGPD, incluindo cuidados com dados pessoais, consentimento quando necessário, transparência e exclusão de dados conforme as regras aplicáveis.

23. INTEGRAÇÕES FUTURAS

Prepare interfaces para conectar posteriormente:

Gateway de pagamento recorrente.

Google Maps ou APIs de empresas autorizadas.

Google Business Profile.

Instagram Graph API.

Facebook Graph API.

WhatsApp Business Platform.

Provedores de IA.

Serviços de hospedagem.

Domínios personalizados.

E-mail transacional.

As integrações devem ser desacopladas para que a plataforma possa funcionar inicialmente sem todas elas.

24. PRIORIZAÇÃO DO MVP

Implemente nesta ordem:

Fase 1 — Núcleo essencial

Landing page.

Cadastro e login.

Perfis de administrador e representante.

Dashboard do representante.

Cadastro de clientes.

Catálogo de serviços.

Propostas comerciais.

Projetos.

Controle financeiro básico.

Dashboard administrativo.

Gestão manual de planos e assinaturas.

Fase 2 — Diferenciais de negócio

Radar de Oportunidades.

Gerador de sites por templates.

Gerador de conteúdo.

Calendário de conteúdo.

Cursos.

Programa de afiliados.

Fase 3 — Automação e escala

Pagamentos recorrentes.

Publicação em redes sociais.

Integrações de IA.

Prospecção por APIs autorizadas.

Domínios personalizados.

Automação de atendimento.

Relatórios avançados.

Aplicativo PWA ou mobile.

Se os créditos forem insuficientes, entregue a Fase 1 totalmente funcional antes de iniciar as fases seguintes.

25. EXPERIÊNCIA DO USUÁRIO

O representante deve conseguir realizar o seguinte fluxo:

Cadastrar-se na Agência MT Web.

Escolher um plano.

Acessar seu dashboard.

Encontrar uma oportunidade de empresa.

Adicionar a empresa ao CRM.

Criar uma proposta.

Registrar a venda.

Criar um projeto.

Gerar o site ou conteúdo do cliente.

Acompanhar a execução.

Registrar receitas e despesas.

Consultar seu desempenho financeiro.

O fluxo deve ser intuitivo, com menus claros, botões de ação e mensagens de confirmação.

26. REQUISITOS TÉCNICOS DE ENTREGA

Desenvolva uma aplicação web responsiva.

Utilize a stack mais econômica e estável disponível no Emergent.

Use banco de dados persistente.

Organize o código de forma modular.

Crie componentes reutilizáveis.

Não implemente funcionalidades fictícias como se fossem reais.

Utilize dados de demonstração apenas para apresentação inicial, identificando-os claramente.

Evite dependências pagas desnecessárias.

Faça validação dos fluxos principais.

Corrija erros de autenticação, permissões e persistência antes de avançar.

Não altere funcionalidades já concluídas sem necessidade.

Ao finalizar cada etapa, informe:

O que foi implementado.

O que está funcionando.

O que depende de API ou credencial externa.

O que ficou preparado para a próxima etapa.

Quais recursos foram adiados para economizar créditos.

27. PRIMEIRA TAREFA

Comece pela Fase 1.

Crie a estrutura inicial da Agência MT Web com:

Landing page pública.

Cadastro e login.

Área administrativa.

Área do representante.

Banco de dados.

Gestão de usuários.

Dashboard.

Cadastro de clientes.

Catálogo de serviços.

Propostas comerciais.

Gestão de projetos.

Financeiro básico.

Gestão manual de planos e assinaturas.

Não desenvolva todas as integrações avançadas neste primeiro momento.

Priorize uma base funcional, visualmente profissional, segura, econômica e preparada para crescimento.

Antes de iniciar recursos que consumam muitos créditos, mantenha o MVP navegável e funcional e apresente o resultado para validação.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://mt-web-connect.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/e7a51ed6-03c0-4372-b3e2-e1b605843e55).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
