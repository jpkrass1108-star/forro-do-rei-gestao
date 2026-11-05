# Forró do Rei — Gestão de Escola de Dança

### Tecnologia aplicada à gestão, às finanças e à experiência do aluno

Sistema web desenvolvido por **João Pedro Krass Ramalho** para centralizar a operação do **Forró do Rei**, uma escola de dança com cinco unidades (Centro, São Mateus, Benfica, Quintas e Fábrica). A aplicação reúne gestão acadêmica, controle financeiro, presença por selfie, reposições, exames de troca de colar e comunicação com alunos, professores e equipe administrativa.

O projeto conecta minha experiência com a rotina da escola ao desenvolvimento de soluções digitais para necessidades reais de negócio.

> Repositório de apresentação do projeto. O código-fonte, as credenciais e os dados internos da aplicação não são disponibilizados.

## O problema de negócio

A gestão de uma escola de dança com múltiplas unidades envolve desafios como organizar a grade de aulas, controlar matrículas e planos, acompanhar a frequência dos alunos, gerenciar a remuneração de professores por hora-aula e manter a comunicação ativa com diferentes públicos.

O sistema foi construído para substituir controles manuais e planilhas dispersas, oferecendo uma interface única e responsiva para cada perfil de usuário.

## Minha contribuição

Desenvolvimento do sistema web a partir do levantamento das necessidades da escola, com definição das regras de negócio, organização das interfaces, fluxos de navegação e recursos de gestão.

Minha atuação na escola contribui para compreender as demandas de alunos, professores e administração, transformando-as em funcionalidades concretas.

## Arquitetura e stack

| Item | Descrição |
| --- | --- |
| Backend | PHP 8.1+ com MySQL/MariaDB, sem frameworks externos |
| Frontend | HTML, CSS e JavaScript próprios, sem dependências de terceiros |
| Arquitetura | Monólito com front controller, rotas centralizadas e CSRF automático |
| Banco de dados | 59 tabelas e 2 views, com migrações versionadas |
| Hospedagem | Hostinger (plano compartilhado), com cron de tarefas a cada 5 minutos |

A ausência de frameworks e dependências externas simplifica a hospedagem compartilhada e reduz custos operacionais, mantendo a aplicação leve e de fácil manutenção.

## Recursos apresentados

| Área | Recursos demonstrados nas telas |
| --- | --- |
| Área do aluno | Próxima aula, avisos, atalhos para check-in, mensalidades, reservas e fotos. |
| Agenda | Consulta de aulas, datas, horários, unidades, professores e ocupação de vagas. |
| Mensalidades | Visualização do plano, vencimentos, cobranças, valores em aberto e situação dos pagamentos. |
| Pagamentos | Fluxo de encaminhamento ao checkout do Mercado Pago (Pix, cartão e boleto). |
| Painel de gestão | Indicadores de alunos pagantes, aulas do dia, presenças a validar, valores recebidos e inadimplência. |
| Perfis | Interfaces específicas para direção, aluno, professor, bolsista e desenvolvedor. |
| Busca de módulos | Pesquisa global para localizar ferramentas e páginas do sistema. |
| Responsividade | Adaptação da navegação, agenda e painéis para telas menores. |

## Interface e experiência de uso

A identidade visual utiliza amarelo, preto e branco, com navegação lateral no computador e adaptação para barra inferior em dispositivos móveis.

A organização por perfil busca tornar as informações e ferramentas relevantes mais acessíveis para cada usuário, respeitando permissões granulares concedidas de forma global ou por unidade.

## Capturas de tela

As imagens abaixo documentam a interface durante o desenvolvimento e os testes. Dados, avisos e estados exibidos representam o momento de cada captura.

### Área do aluno

Acesso às próximas aulas, avisos e principais ações do dia a dia, como check-in, pagamento de mensalidade, reserva de aula e visualização de fotos.

![Área do aluno](Tela%204.png)

### Agenda de aulas

Consulta de horários, unidades, professores, ocupação de vagas e filtros por dia ou semana.

![Agenda de aulas](Tela%201.png)

### Mensalidades e cobranças

Visualização do plano contratado, valores em aberto, histórico de cobranças e opção de pagamento.

![Mensalidades e cobranças](Tela%208.png)

### Painel de gestão

Visão consolidada de indicadores e aulas do dia. A captura também exibe um aviso de configuração pendente das tarefas agendadas naquele ambiente.

![Painel de gestão](Tela%205.png)

### Perfis de acesso

Alternância entre os diferentes contextos de utilização do sistema, como direção geral, aluno, professor, bolsista e desenvolvedor.

![Perfis de acesso](Tela%202.png)

### Busca de ferramentas

Pesquisa de módulos para facilitar a navegação e o acesso rápido a funcionalidades.

![Busca de ferramentas](Tela%203.png)

### Visualização mobile

Agenda apresentada em uma simulação de tela de celular durante os testes de responsividade.

![Visualização mobile](Tela%206.png)

## Integração com pagamentos

O projeto inclui um fluxo de encaminhamento de cobranças ao checkout do Mercado Pago, com suporte a Pix, cartão e boleto.

A captura do checkout não integra esta galeria por apresentar informações pessoais da conta utilizada no teste. A abertura do checkout demonstra o encaminhamento ao provedor, mas não comprova, isoladamente, a conclusão do pagamento ou a baixa automática da cobrança.

## Competências demonstradas

- Transformação de necessidades operacionais em funcionalidades.
- Desenvolvimento de interfaces para diferentes perfis de usuário.
- Organização de informações financeiras e administrativas.
- Integração de um fluxo de cobrança com provedor de pagamentos.
- Construção e avaliação de interfaces responsivas.
- Aplicação de tecnologia à gestão de um negócio real.

## Estado do projeto

Projeto em evolução. As capturas demonstram interfaces e fluxos disponíveis no ambiente apresentado; não representam validação completa de todos os processos.

Os resultados de redução de trabalho manual e melhoria da organização são objetivos do sistema, sem métricas de impacto apresentadas neste portfólio.

## Autor

**João Pedro Krass Ramalho**

Estudante de Ciências Contábeis na UFJF e de Análise e Desenvolvimento de Sistemas na Estácio.

**Objetivo profissional:** unir tecnologia e finanças para desenvolver soluções que simplifiquem processos e apoiem decisões de negócio.
