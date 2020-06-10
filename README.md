# Summary
The applications of digital voice processing, such as automatic voice recognition and hands-free voice call communication, suffer from a well-known effect called reverberation, produced by the environment or the room. This effect is the cumulative result of many acoustic reflections and it is present in many places on a daily basis.
Reverberation can degrade speech quality in a voice recognition system, but it also allows listeners to deduce, for example, the properties of the room. In the same way, machines can acquire learning models to obtain properties of their acoustic environments.

Deep Neural Networks have been widely used in the fields of both image and voice processing and have advanced significantly in recent years [2]. Building on previous research [1], this work investigates how deep learning can use the effect of voice reverberation to classify different acoustic environments. Specifically, a system will be designed and evaluated in order to analyze reverberant acoustic environments through deep neural networks that will receive voice signals with reverberation and, subsequently, they will identify the room where the recording was made.

The approaches that were previously taken in similar studies prior to this one, were based on acoustic parameters that were selected "manually" as characteristics used by the classifiers. This way of estimating the values of these parameters from the reverberant speech implies estimation errors, which directly affects the precision of the classification. This work shows how deep neural networks can execute a classification by operating directly on reverberant voice signals without previously selecting any parameters. Throughout the document, a method to train deep learning classifiers and a DNN architecture for this task will be proposed. In addition, different experimental scenarios will be defined to evaluate the performance of the neural network, and an analysis of the obtained results will be carried out.


[1] C. Papayiannis, C. Evers, and P. A. Naylor, "End-to-End Classification of Reverberant Rooms using DNNs," arXiv preprint arXiv:1812.09324, 2018.

[2] W. Liu, Z. Wang, X. Liu, N. Zeng, Y. Liu, and F. E. Alsaadi, “A survey of deep neural network architectures and their applications,” Neurocomputing, vol. 234, pp. 11–26, 2017, doi: 10.1016/j.neucom.2016.12.038.


# Resumen
Las aplicaciones del tratamiento digital de voz, como el reconocimiento de voz automático y la comunicación por llamada de voz con manos libres, sufren un efecto conocido llamado reverberación, producido por el entorno o la sala. Este efecto es el resultado acumulativo de muchas reflexiones acústicas y está presente en muchos lugares de nuestro día a día.
La reverberación puede degradar la calidad del habla en un sistema de reconocimiento de voz, pero también nos permite a los oyentes deducir, por ejemplo, las propiedades de la sala. Del mismo modo, las máquinas pueden utilizar modelos de aprendizaje para obtener propiedades de sus entornos acústicos.

Las Redes Neuronales Profundas (Deep Neural Networks) han sido ampliamente utilizadas en los campos de procesamiento de imágenes y en el procesamiento de voz, y han avanzado significativamente en los últimos años [2]. Basándonos en investigaciones previas [1], este trabajo investiga cómo el aprendizaje profundo puede usar el efecto de la reverberación de la voz para clasificar diferentes entornos acústicos. En concreto, se diseñará y se evaluará un sistema para el análisis de entornos acústicos reverberantes a través de redes neuronales profundas que recibirán señales de voz con reverberación y, posteriormente, identificarán la sala en donde se realizó la grabación.

Los enfoques que se tomaron previamente en estudios similares anteriores a éste se basaban en parámetros acústicos que fueron seleccionados “manualmente” como características utilizadas por los clasificadores. Esta forma de estimación de parámetros a partir de la voz con reverberación puede implicar errores de estimación, lo que afecta directamente a la precisión de la clasificación. Este trabajo muestra cómo las redes neuronales profundas pueden realizar la clasificación operando directamente sobre las señales de voz con reverberación sin seleccionar previamente ningún parámetro acústico. A lo largo del documento, se propondrá un método para el entrenamiento de los clasificadores de aprendizaje profundo y una arquitectura DNN para esta tarea. Además, se definirán diferentes escenarios experimentales en los cuales se evaluará el rendimiento de la red neuronal y se realizará un análisis de los resultados obtenidos.


[1] C. Papayiannis, C. Evers, and P. A. Naylor, "End-to-End Classification of Reverberant Rooms using DNNs," arXiv preprint arXiv:1812.09324, 2018.

[2] W. Liu, Z. Wang, X. Liu, N. Zeng, Y. Liu, and F. E. Alsaadi, “A survey of deep neural network architectures and their applications,” Neurocomputing, vol. 234, pp. 11–26, 2017, doi: 10.1016/j.neucom.2016.12.038.
