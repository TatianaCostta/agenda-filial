AGENDA 8340

Sistema web criado para a filial 8340 da CVC Viagens (MAG Shopping, João Pessoa/PB), para substituir controles manuais de escala de folgas e acompanhamento de viagens de clientes por uma ferramenta centralizada e com alertas automáticos.

O problema
A gestão da escala de folgas de fins de semana e feriados trabalhados era feita manualmente, assim como o acompanhamento de embarques e pós-venda dos clientes da filial. Isso gerava retrabalho, risco de esquecimento de avisos importantes (folgas, check-in de voos) e dificuldade de rastrear o histórico da equipe, que tem alta rotatividade.

Meu papel
Concebi, especifiquei os requisitos e validei o sistema com a equipe da filial, atuando como responsável de produto ao longo de todo o processo, da identificação do problema ao teste com usuários reais. O desenvolvimento foi conduzido com apoio de IA generativa, sob minha orientação e decisões de escopo.

Requisitos levantados
Com base nas necessidades da equipe, defini:
-Cadastro e exclusão livre de colaboradores (para lidar com a alta rotatividade da equipe)
-Edição da escala de folgas diretamente pela gestora
-Alerta automático 24h antes da folga de um colaborador
-Etiquetas coloridas para sinalizar diferentes tipos de aviso
-Acesso dos colaboradores para incluir avisos (ex: consulta médica, atestado), sem permissão para alterar o que a gestora insere
-Cadastro de viagens de clientes: data de embarque, nome do cliente, recibo da venda, destino
-Alerta ao colaborador 48h antes do embarque (24h para voos internacionais) e 7 dias antes para checagem do status do voo

Funcionalidades
-Gestão de escala de folgas e feriados trabalhados da equipe
-Registro e acompanhamento de embarques de clientes, com destino nacional ou internacional
-Sistema de alertas configurados por prazo e tipo de evento
-Login individual por nome + senha
-Painel de acesso diferenciado entre gestora e colaboradores

Processo de validação
O sistema foi testado com a equipe da filial, o que permitiu identificar ajustes necessários, como a inclusão de um campo de anotações no cadastro de embarque e melhorias de acesso via celular, incorporados em iterações seguintes.

Stack
-Firebase / Firestore (armazenamento e autenticação)
-Desenvolvimento assistido por IA generativa, sob orientação e validação da autora

Aprendizados
Este projeto reforçou minha experiência em levantamento de requisitos junto a usuários reais, priorização de funcionalidades com base em impacto operacional, e validação iterativa de produto, habilidades centrais para atuação em Coordenação de Projetos e Product Ownership.
