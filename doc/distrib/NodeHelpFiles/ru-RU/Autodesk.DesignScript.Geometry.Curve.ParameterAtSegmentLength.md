## Подробности
ParameterAtSegmentLength возвращает параметр точки, которая находится на кривой на расстоянии от начальной точки, равном заданной длине. В примере ниже сначала с помощью узла ByControlPoints создается NURBS-кривая, где в качестве входных элементов используется набор случайных точек. Числовой регулятор используется для управления длиной сегмента, на расстоянии которого требуется найти параметр. Если входная длина сегмента превышает длину кривой, этот узел возвращает значение параметра в конечной точке кривой.
___
## Файл примера

![ParameterAtSegmentLength](./Autodesk.DesignScript.Geometry.Curve.ParameterAtSegmentLength_img.jpg)
