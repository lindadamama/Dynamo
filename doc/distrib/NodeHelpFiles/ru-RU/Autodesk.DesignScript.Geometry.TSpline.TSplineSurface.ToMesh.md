## Подробности
В приведенном ниже примере простая Т-сплайновая поверхность рамки преобразуется в сеть с помощью узла `TSplineSurface.ToMesh`. Входной параметр `minSegments` определяет минимальное количество сегментов для грани в каждом направлении. Он важен для управления определением сети. Входной параметр `tolerance` исправляет неточности путем добавления дополнительных положений вершин для соответствия исходной поверхности в пределах заданного допуска. Результатом является сеть, предварительный просмотр определения которой выполняется с помощью узла `Mesh.VertexPositions`.
Выходная сеть может содержать как треугольники, так и квадраты, что важно учитывать при использовании узлов MeshToolkit.
___
## Файл примера

![TSplineSurface.ToMesh](./Autodesk.DesignScript.Geometry.TSpline.TSplineSurface.ToMesh_img.jpg)