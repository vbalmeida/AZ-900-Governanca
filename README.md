# AZ-900-Governanca

# Governança e Conformidade

# Azure Policy

As políticas do Azure servem para que nós possamos criar padrões de conformidade referentes a recursos dentro de nossa organização.

Cria um padrão para criação dos recursos. Determinando certas regras, independente de quem esteja criando.

Caso uma Policy seja criada após os meus recursos, essas regras não serão aplicadas aos recursos já existentes.

No-compliant: Sinaliza que meu recurso não está de acordo com a minha Policy.
Remediation: Fazer alteração do status do que já existe.
Compliant: Diz que todos os itens estão seguindo o padrão esperado.




# Bloqueio de Recursos

Proteja os recursos do Azure de exclusão ou modificação acidental.

Bloqueios são herdáveis. Então se eu colocar o bloqueio lá no nível da assinatura, tudo que está nela recebe. A mesma coisa no grupo de recursos.

Tipos de bloqueios:
Excluir - Posso Ler e Atualizar / Não posso Excluir
ReadOnly - Posso Ler / Não posso atualizar ou Excluir.

# Portal de Confiança do Serviço

É um link aberto ao público, onde temos acessos às informações que a Microsoft utiliza para proteção de dados, validação de conteúdos para IA, regra, protocolos etc.

 


# Microsoft Purview

Serve para gerenciamento de governança, risco e conformidade.
Descoberta de dados automatizados.
Classificação de dados confidenciais.
Linhagem de dados de ponta a ponta.
