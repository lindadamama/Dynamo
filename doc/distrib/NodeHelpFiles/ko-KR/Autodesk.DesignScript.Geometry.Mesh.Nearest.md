## 상세
`Mesh.Nearest`는 지정된 점에 가장 가까운 입력 메쉬의 점을 반환합니다. 반환되는 점은 점을 통과하는 메쉬의 법선 벡터를 사용하여 입력 점을 메쉬에 투영한 것이며, 이는 가장 가까운 점이 됩니다.

아래 예제에서는 노드의 작동 방식을 보여주는 간단한 사용 사례가 생성됩니다. 입력 점은 구형 메쉬 위에 있지만 바로 위에 있지는 않습니다. 결과 점은 메쉬 위에 놓여 있는 가장 가까운 점입니다. 이는 결과 점이 입력 점 바로 아래의 메쉬에 투영되는 `Mesh.Project` 노드의 출력(음의 'Z' 방향 벡터와 함께 같은 점과 메쉬를 입력으로 사용)과 비교됩니다. `Line.ByStartAndEndPoint`는 메쉬에 투영된 점의 '궤적'을 표시하는 데 사용됩니다.

## 예제 파일

![Example](./Autodesk.DesignScript.Geometry.Mesh.Nearest_img.jpg)