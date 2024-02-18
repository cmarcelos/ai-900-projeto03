# Como fazer o projeto de "Análise de Sentimentos com o Language Studio no Azure Ai"

## Conhecendo o Estudio de fala.

1. Entre no site <https://speech.microsoft.com/portal>
2. Clique na engrenagem.
3. Em criar novo recurso preeencha:
    - Nome do recurso: Crie um nome.
    - Assinatura: "vai ter a sua, selecione"
    - Região: Leste dos EUA
    - Padrão: SO
    - Grupo de reccurso: "dê um nome a sua escolha"
4. Crie o recurso.
5. Clicar em ==> Usar recurso
6. Ir para "Conversão de fala em texto"
7. E selecionar ==> Conversão de Fala em texto em tempo real
8. colar o texte no local e pronto. A conversão e realizada.

[!Nota]: O texto gerado foi 100% fiel ao audio. Tambem fiz o teste para fala, ou seja eu fiz um ditado e o resultado foi 100% correto.

## Conhecendo o Language Studio

1. Entre no portal do Azure <https://portal.azure.com/#home>
1. Clique no "+" criar um recurso. IA + MachineLearning
3. Depois em - Análise de texto / Language Service
4. Criar
5. <font color="blue">Continue para criar seu recurso</font>

6. Assinatura: Se não tiver senecionado escolha a sua.
7. Grupo de recurso: Criar novo -> Dê um nome a seu recurso.
8. Região: East EUA
9. Nome: Dê um de sua preferência.
10. Tipo $: Escolha - Free F0 ...
11. [x] Deixa a caixa checada.

12. <font color="blue">Examinar e criar</font>
13. <font color="blue">Criar</font>
14. Ao finalizar.
15. <font color="blue">Ir para o crupo de recursos</font>


16. Abrir nova aba, indo para o link <https://language.cognitive.azure.com/>
17. Entrar no conta, caso não esteja conectado.
18. Vai pedir para selecionar os recursos.

19. Azure diretório: Padrão
20. Azure Subscription: Escolha conforme colocou no item 6 desta descrição.
21. Resource type: Language
22. Resource Name: Escolha conforme colocou no item 9 desta descrição.
23. <font color="blue">Dove</font>
24. <font color="blue">Criate New</font> (Este passo fiz pq a instrutora soliciou, mas não percebi nada na pratica)
25. <font color="blue">Classify text</font>
26. <font color="blue">Analisar sentimentos e opniões</font>
27. Digito o texto ou pego um exemplo na internet.
28. [x] I acknoledge ... (deixe ticado)
29. <font color="blue">Run</font>

30. Faça sua analise com o dados apresentados. 