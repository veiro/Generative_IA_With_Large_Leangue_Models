# Generative_IA_With_Large_Leangue_Models1. 

## segameaker de aws como usar sagemaker  (es pago)
Esta es la guia del curos: https://labs.vocareum.com/main/main.php?m=clabide&mode=s&asnid=1843537&stepid=1843538&hideNavBar=1 


1. https://github.com/veiro/Generative_IA_With_Large_Leangue_Models/blob/main/Lab_1_summarize_dialogue.ipynb
   
Resumen: Carga el model T5 y hacer fewshots traingng para ver como mejora los resultados en resumen de dialogo https://www.coursera.org/learn/generative-ai-with-llms/gradedLti/loNJu/lab-1-generative-ai-use-case-summarize-dialogue.

Explicacion del laboratorio https://www.coursera.org/learn/generative-ai-with-llms/lecture/wno7h/lab-1-walkthrough 

4.  https://github.com/veiro/Generative_IA_With_Large_Leangue_Models/blob/main/Lab_2_fine_tune_generative_ai_model.ipynb Fine-tuning
   
Resumen: usando soft propmts de un modelo T5. Luego Fine-tuning con la tecnica PEFT y compara con flan-T5 que es uno finetuneado por ellos. Comapra con la metrica ROGUE como funciona el resumen. En resumen el de ellos es mejor, pero llevo mucho mas computo que las tecnicas utilizadas en este laboratorio.

Explicacion del laboratorio https://www.coursera.org/learn/generative-ai-with-llms/lecture/A6TDx/lab-2-walkthrough 
   
5. https://github.com/veiro/Generative_IA_With_Large_Leangue_Models/blob/main/Lab_3_fine_tune_model_to_detoxify_summaries.ipynb
   
Resumen: En este cuaderno, ajustará un modelo FLAN-T5 para generar contenido menos tóxico mediante el modelo de recompensa por incitación al odio de Facebook. El modelo de recompensa es un clasificador binario que predice "no odiar" u "odiar" por el texto dado. Utilizará la optimización de políticas próximas (PPO) para ajustar y desintoxicar el modelo. 

Explicacion del laboratorio https://www.coursera.org/learn/generative-ai-with-llms/lecture/yPzI4/lab-3-walkthrough 
