---
name: illustration-review
description: Usa esta skill para avaliar uma ilustração ou conjunto de ilustrações contra um sistema de ilustração e um plano de produção aprovados. Produz uma revisão objetiva e instruções de correção. Não a uses para gerar imagens, redesenhar a peça ou inventar critérios que não existam no contexto.
---

# Revisão de ilustração

Usa esta skill para verificar uma ilustração produzida face a um sistema de ilustração e a um plano de produção já aprovados. A revisão deve ser rastreável à evidência acessível e resultar em correções concretas, sem alterar a direção visual aprovada.

## Contexto necessário

Antes de avaliar, exige ou identifica explicitamente como informação em falta:

- o sistema de ilustração aprovado;
- o plano de produção aprovado;
- a imagem ou imagens a avaliar;
- a aplicação, o formato e os requisitos técnicos;
- o objetivo concreto da revisão.

Considera um sistema ou plano aprovado apenas quando o utilizador o declarar de forma explícita ou quando a aprovação for inequívoca no contexto. Não trates propostas, referências, moodboards ou versões de trabalho como aprovação.

Se uma imagem não tiver sido fornecida ou não estiver acessível, declara que não a pudeste observar. Não afirmes, sugiras ou impliques que a viste. Nesse caso, limita a revisão ao contexto documental disponível, identifica o que impede a avaliação visual e não inventes observações sobre a peça.

Quando faltar informação, mantém a revisão proporcional: regista a lacuna, explica que conclusão ela limita e avalia apenas o que a evidência permite.

## Separação da evidência

Distingue sempre, de forma visível, as seguintes categorias:

- **Observações visuais confirmáveis** — elementos que são diretamente verificáveis nas imagens acessíveis ou nos ficheiros fornecidos.
- **Interpretações** — leituras fundamentadas das observações e do sistema ou plano aprovados; não as apresentes como factos.
- **Limitações da evidência** — materiais em falta, imagens inacessíveis, resolução insuficiente, ângulos ausentes ou requisitos não confirmados.
- **Riscos de semelhança excessiva** — apenas quando a evidência permite comparar a peça com referências ou elementos distintivos identificados. Descreve a base concreta do risco; se não existir base, indica que não foi possível avaliá-lo.
- **Recomendações de correção** — ações específicas, proporcionais e alinhadas com o sistema aprovado.

Não inferas propriedades técnicas que não sejam confirmáveis no material acessível. Não transformes uma interpretação, uma hipótese ou uma recomendação numa observação visual.

## Critérios de avaliação

Avalia, apenas na medida em que os materiais o permitirem:

- clareza da ideia e da sequência de leitura;
- composição, hierarquia e legibilidade;
- coerência com o sistema de ilustração aprovado;
- componentes, linha, cor, textura, escala e recorte;
- adequação à aplicação, ao formato e aos requisitos técnicos;
- elementos excluídos, contradições com o plano ou com o sistema;
- risco de aproximação excessiva a referências, só quando houver base concreta para essa conclusão.

Compara a peça com regras, componentes, exclusões e critérios que constem do sistema e do plano aprovados. Não inventes critérios para preencher lacunas nem proponhas uma direção visual nova sem pedido explícito.

## Estrutura obrigatória da entrega

Entrega a revisão pela ordem seguinte, com títulos claros:

### 1. Âmbito e evidência disponível

Indica a peça ou conjunto avaliado, o objetivo da revisão, os materiais acessíveis, as aprovações confirmadas e as lacunas relevantes. Declara expressamente quando uma imagem não foi fornecida ou não está acessível.

### 2. Observações confirmáveis

Abre esta secção com **Observações visuais confirmáveis** e regista apenas o que é diretamente verificável. Se não houver evidência visual acessível, diz que não existem observações visuais confirmáveis e não preenchas esta secção com suposições.

### 3. Coerência com o sistema

Abre esta secção com **Interpretações** e relaciona-as com as regras, os componentes e as exclusões do sistema aprovado, e com as decisões do plano de produção. Não apresentes interpretações como observações. Assinala os critérios que não podem ser avaliados.

### 4. Pontos que funcionam

Identifica os aspetos confirmados que cumprem o sistema, o plano ou os requisitos técnicos. Não atribuas méritos sem evidência suficiente.

### 5. Problemas a corrigir

Apresenta apenas problemas sustentados pela evidência numa tabela com estas colunas:

| Gravidade | Evidência | Ação concreta |
| --- | --- | --- |

Usa **bloqueante**, **alta**, **média** ou **baixa** conforme o impacto no objetivo, na coerência do sistema, na legibilidade ou na entrega técnica. A ação concreta deve indicar o que ajustar, o que preservar e o critério que confirma a correção, sem redesenhar a peça.

### 6. Riscos e limitações

Abre esta secção com **Limitações da evidência** e separa-as dos riscos de produção e dos **Riscos de semelhança excessiva**. Para qualquer risco de semelhança, indica o elemento comparado e a evidência que o sustenta. Se as referências necessárias não estiverem acessíveis, declara que esse risco não pôde ser avaliado.

### 7. Brief de revisão para a skill `illustration-production`

Resume somente as correções aprováveis para a próxima iteração: objetivo, ajustes prioritários, elementos a preservar, exclusões e critérios de validação. Não incluas um prompt de geração, não peças uma nova direção visual e não produzas nem edites imagens.

### 8. Decisão final

Escolhe uma destas decisões e justifica-a com a evidência disponível:

- **Aprovar** — a peça cumpre os critérios avaliáveis e não há problema bloqueante ou de alta gravidade.
- **Rever** — existem correções concretas e limitadas que devem ser aplicadas antes de aprovação.
- **Bloquear** — falta evidência, aprovação, requisito ou acesso à imagem indispensável para uma avaliação responsável, ou existe uma contradição fundamental que impede a continuação.

### 9. Próximo passo

Indica a ação mínima e concreta: fornecer material em falta, validar uma decisão, corrigir os problemas listados ou encaminhar o brief de revisão para `illustration-production`.

## Limites de atuação

- Não cries nem edites imagens.
- Não redesenhes a peça nem proponhas uma nova direção visual sem pedido explícito.
- Não instales dependências, não navegues na web nem alteres ficheiros durante a utilização desta skill, salvo pedido explícito do utilizador.
- Trabalha em português de Portugal, com linguagem concreta.
- Mantém a revisão proporcional ao material acessível.
