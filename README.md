# Apoio ao Rastreio do Câncer de Mama com Aprendizado de Máquina:
Projeto desenvolvido para a disciplina de **Inteligência Artificial em Engenharia Biomédica**, focado no desenvolvimento e avaliação de modelos de Machine Learning para auxílio ao diagnóstico precoce do câncer de mama a partir de dados de Ultrassonografia (USG) validados por biópsias.
# Objetivo:
A fim de consolidar o uso da ferramenta WEKA, foram conduzidos experimentos a partir de uma base de dados (Lenet_ultrassonografia.arff). O projeto demonstrou a eficácia e a viabilidade da aplicação de técnicas de Aprendizado de Máquina em dados de ultrassonografia para o suporte ao diagnóstico precoce do Câncer de Mama.
# Metodologia: 
Base de Dados - Composta por 879 instâncias e 501 atributos numéricos, apresentando classes desbalanceadas.
Redução de Dimensionalidade - Algoritmo Genético (AG) Reduziu o conjunto para 255 atributos (50 gerações e 100 iterações).
Otimização por Enxame de Partículas (PSO)- Reduziu o conjunto para 104 atributos (50 gerações e 100 iterações).
Tratamento de Dados - Balanceamento de classes via SMOTE.
Validação - Validação cruzada 10-fold (5 execuções) para garantir a confiabilidade dos resultados e mitigar o overfitting.
Classificadores Testados - Árvores de Decisão, modelos Bayesianos e Máquinas de Vetores de Suporte (SVM).
# Resultados 
O classificador que mais se destacou foi o Random Forest (200 árvores), que atingiu os melhores índices em:
Acurácia
Métrica Kappa
Sensibilidade
Especificidade
O modelo destacou-se em ambas as abordagens de seleção de atributos (AG e PSO) e sobressaiu-se por exigir o menor custo operacional quando confrontado com as demais configurações do próprio Random Forest. Essa escolha favorece não apenas a eficácia do modelo, mas também sua aplicabilidade em cenários clínicos que demandam soluções rápidas e precisas.
