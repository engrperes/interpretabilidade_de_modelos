# interpretabilidade_de_modelos

A interpretabilidade em Machine Learning (ML) refere-se à capacidade de entender e explicar como um modelo toma suas decisões. Em muitas aplicações — especialmente em áreas como saúde, finanças e direito —, não basta ter um modelo preciso; é crucial saber por que ele chegou a determinado resultado.

📌 Por que a interpretabilidade importa?
• Transparência: Ajuda a confiar no modelo, especialmente em decisões críticas.
• Conformidade: Atende a regulamentações como GDPR (direito à explicação).
• Depuração: Facilita a identificação de vieses e erros no modelo.
• Validação humana: Permite que especialistas validem as decisões do modelo.

🔍 Técnicas Comuns
1. Modelos Intrínsecos: Árvores de decisão, regressão linear — fáceis de interpretar por natureza.
2. Pós-processamento:
  • SHAP/SHAP Values: Mostra a contribuição de cada feature na previsão.
  • LIME: Explica previsões individuais com um modelo local simples.
  • Importância de Features: Rankeia variáveis por influência no resultado.

Se o seu projeto exige transparência, considere equilibrar desempenho e explicabilidade. Caso contrário, modelos "caixa-preta" (como redes neurais profundas) podem ser mais eficientes, mas menos interpretáveis.
