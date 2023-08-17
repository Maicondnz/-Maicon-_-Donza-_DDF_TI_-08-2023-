1. **Coleta e Análise de Dados:**
   - Coletaria feedback dos clientes, incluindo avaliações de satisfação e informações sobre a taxa de churn.
   - Coletaria dados de suporte, como número de tickets abertos, tempos de resposta e resolução, além de problemas recorrentes.
   - Usando os dados de feedback, desenvolveria uma medida de sentimento para identificar clientes que necessitam de atenção especial.
   - Analisaria os dados dos tickets para avaliar tempos médios de resposta e a eficácia da resolução no primeiro contato.
   - Segmentaria os dados por tipo de produto, datas e características dos clientes para identificar padrões de demanda, avaliar o desempenho da equipe de suporte ao longo do tempo e identificar características comuns entre clientes com problemas similares. Esses insights seriam usados para automatizar respostas para certos tipos de chamados.

2. **Transição de Plataforma de Gerenciamento:**
   - Informaria toda a equipe sobre as mudanças planejadas.
   - Implementaria as mudanças de maneira gradual, começando por áreas de menor complexidade e escolhendo dias estratégicos para minimizar interrupções.
   - Realizaria testes contínuos para medir o desempenho e a satisfação na nova plataforma.
   - Ofereceria treinamento à equipe para garantir o melhor uso da nova abordagem.

3. **Praticas para Implementar Gestão de Acesso:**
   - Estabeleceria monitoramento de comportamento de acesso.
   - Implementaria medidas de segurança, como a troca regular de senhas, tokens e chaves.
   - Controlaria o acesso com base nas funções de cada usuário.
   - Forneceria treinamento em segurança aos utilizadores.

4. **Atendimento ao Cliente com Chatbot:**
   - Utilizaria chatbots para atender a questões mais comuns e menos complexas.
   - Manteria a opção de atendimento humano disponível.
   - Planejaria testar um atendimento 100% via chatbot posteriormente, comparando os índices de satisfação do cliente para determinar a melhor abordagem.

5. **Consulta SQL:**
   - Executaria a seguinte consulta SQL para obter endereços de e-mail de usuários registrados nos últimos 30 dias:
    
    SELECT * (seleciona todas as colunas)

    FROM users_emails (escolha da tabela)

    WHERE registration_date >= DATE_SUB(CURRENT_DATE, INTERVAL 30 DAY);
     
     **WHERE** (filtra por um parametro )

     **registration_date** (coluna com data de registro)
     
     **DATE_SUB** (subtrai um intervalo de data )

     **CURRENT_DATE** (seleciona data atual)

     **INTERVAL 30 DAY** (identifica o tamanho do intervalo)



