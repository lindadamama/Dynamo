<!--- Autodesk.DesignScript.Geometry.TSpline.TSplineSurface.ByTorusCoordinateSystemRadii --->
<!--- TTAJ2WGGNFLM755ADOCD3G7N4MJBQI66CAC7SXM3XCYLEIPLBOCQ --->
## In-Depth
No exemplo abaixo, é criada uma superfície de toroide da T-Spline com sua origem em determinado sistema de coordenadas `cs`. Os raios menor e maior da forma são definidos pelas entradas `innerRadius` e `outerRadius`. Os valores de `innerRadiusSpans` e `outerRadiusSpans` controlam a definição da superfície ao longo das duas direções. A simetria inicial da forma é especificada pela entrada `symmetry`. Se a simetria axial aplicada à forma estiver ativa para o eixo X ou Y, o valor de `outerRadiusSpans` do toroide deverá ser um múltiplo de 4. A simetria radial não tem esse requisito. Por fim, a entrada `inSmoothMode` é usada para alternar entre a visualização suave e de caixa da superfície da T-Spline.

## Arquivo de exemplo

![Example](./TTAJ2WGGNFLM755ADOCD3G7N4MJBQI66CAC7SXM3XCYLEIPLBOCQ_img.jpg)
