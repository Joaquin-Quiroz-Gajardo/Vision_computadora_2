# Kannada MNIST

La base de datos de Kannada MNIST contiene imágenes en escala de grises con dígitos escritos desde el 0 al 9, bajo la tipografía Kannada. Al igual que en la versión original de MNIST las imágenes poseen una dimensión de 28*28 pixeles. Diferentes modelos pre-entrenados fueron implementados para clasificar esta base, asistidos por técnicas de data augmentation para optimizar la información provista por el conjunto de datos, obteniendo los siguientes resultados.

| Models pretrain models | Accuracy |
|------------------------|----------|
| vgg16                  | 99.025   |
| resnet50               | 98.191   |
| resnet18               | 98.191   |
| alexnet                | 96.525   |
| mnasnet                | 96.05    |
| shufflenet             | 56.591   |