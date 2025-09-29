# Codegirls_Desafio-EBS-EC2
Este repositório tem como objetivo documentar o meu aprendizado na DIO, em parceria com o Santander, no Boot Camp Code Girls 2025. Neste primeiro desafio, estarei demostrando sobre o processo de S3,EC2,Lambda e EBS.

A arquitetura abaixo representa o processamento de imagem na AWS.
<img width="957" height="627" alt="Captura de Tela 2025-09-29 às 07 42 24" src="https://github.com/user-attachments/assets/8883ef6e-80d1-4a3f-974a-22624b905067" />

Disponibilizei a arquitetura no link:[EBS_EC2_S3_Lambda.drawio](https://github.com/user-attachments/files/22595690/EBS_EC2_S3_Lambda.drawio)
<mxfile host="Electron" agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/28.1.2 Chrome/138.0.7204.243 Electron/37.4.0 Safari/537.36" version="28.1.2">
  <diagram name="Página-1" id="fw2uBaiAmZ4nlsC1iYkD">
    <mxGraphModel dx="976" dy="649" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" background="light-dark(#fb93c5, #121212)" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="q2Auk95UIFfUWz-NXu3p-23" value="" style="ellipse;shape=cloud;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="70" width="910" height="640" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-3" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="169" y="253" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-1" value="Usuário" style="verticalLabelPosition=bottom;shadow=0;dashed=0;align=center;html=1;verticalAlign=top;strokeWidth=1;shape=mxgraph.mockup.containers.userFemale;strokeColor=#666666;strokeColor2=#008cff;" vertex="1" parent="1">
          <mxGeometry x="19" y="208" width="90" height="90" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-4" value="Amazon S3&lt;div&gt;1.UPLOAD DE IMAGENS&lt;/div&gt;" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=none;strokeColor=#ffffff;fillColor=#232F3E;dashed=0;verticalLabelPosition=middle;verticalAlign=bottom;align=center;html=1;whiteSpace=wrap;fontSize=10;fontStyle=1;spacing=3;shape=mxgraph.aws4.productIcon;prIcon=mxgraph.aws4.s3;" vertex="1" parent="1">
          <mxGeometry x="169" y="208" width="80" height="120" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-5" target="q2Auk95UIFfUWz-NXu3p-6">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-11" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-5" target="q2Auk95UIFfUWz-NXu3p-10">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="509" y="169" />
              <mxPoint x="509" y="169" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-5" value="Amazon S3&lt;div&gt;UPLOAD DE IMAGENS&lt;/div&gt;" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=none;strokeColor=#ffffff;fillColor=#232F3E;dashed=0;verticalLabelPosition=middle;verticalAlign=bottom;align=center;html=1;whiteSpace=wrap;fontSize=10;fontStyle=1;spacing=3;shape=mxgraph.aws4.productIcon;prIcon=mxgraph.aws4.s3;" vertex="1" parent="1">
          <mxGeometry x="419" y="138" width="70" height="120" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-8" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-6" target="q2Auk95UIFfUWz-NXu3p-5">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="344.29999999999995" y="196.5" as="targetPoint" />
            <Array as="points">
              <mxPoint x="344" y="198" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-15" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-6" target="q2Auk95UIFfUWz-NXu3p-14">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-6" value="LAMBDA&lt;div&gt;(PROCESSAMENTO&lt;/div&gt;&lt;div&gt;OTIMIZA A IMAGEM)&lt;/div&gt;" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.lambda;fillColor=#F58534;gradientColor=none;" vertex="1" parent="1">
          <mxGeometry x="306" y="278" width="76.5" height="83" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-10" value="S3&lt;div&gt;(IMAGENS PROCESSADAS)&lt;/div&gt;" style="sketch=0;points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;fontColor=#232F3E;fillColor=#7AA116;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=12;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.s3;" vertex="1" parent="1">
          <mxGeometry x="569" y="130" width="78" height="78" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-12" value="S3&lt;div&gt;(VISUALIZA ACESSA O S3/&lt;/div&gt;&lt;div&gt;IMAGENS)&lt;/div&gt;" style="sketch=0;points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;fontColor=#232F3E;fillColor=#7AA116;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=12;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.s3;" vertex="1" parent="1">
          <mxGeometry x="749" y="159" width="78" height="78" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-13" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-10" target="q2Auk95UIFfUWz-NXu3p-12">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-14" value="EC2(APLICAÇÃO WEB/BANCO DE DADOS)" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.ec2_compute_container_3;fillColor=#F58534;gradientColor=none;" vertex="1" parent="1">
          <mxGeometry x="479" y="298" width="200" height="100" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-16" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-12" target="q2Auk95UIFfUWz-NXu3p-14">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="789" y="348" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-17" value="EBS" style="verticalLabelPosition=bottom;html=1;verticalAlign=top;strokeWidth=1;align=center;outlineConnect=0;dashed=0;outlineConnect=0;shape=mxgraph.aws3d.ebs;fillColor=#ECECEC;strokeColor=#5E5E5E;aspect=fixed;strokeColor2=#292929;" vertex="1" parent="1">
          <mxGeometry x="519" y="448" width="92" height="60" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-18" value="2.Nova imagem" style="shape=document;whiteSpace=wrap;html=1;boundedLbl=1;" vertex="1" parent="1">
          <mxGeometry x="150" y="70" width="70" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-19" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;flowAnimation=1;dashed=1;" edge="1" parent="1" source="q2Auk95UIFfUWz-NXu3p-18" target="q2Auk95UIFfUWz-NXu3p-6">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="286" y="320" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-21" value="&lt;span style=&quot;text-wrap-mode: nowrap; background-color: rgb(255, 255, 255);&quot;&gt;&lt;font style=&quot;font-size: 8px;&quot;&gt;3.Salva a imagem&amp;nbsp;&lt;/font&gt;&lt;/span&gt;&lt;div style=&quot;text-wrap-mode: nowrap;&quot;&gt;&lt;font style=&quot;font-size: 8px;&quot;&gt;processada&lt;/font&gt;&lt;/div&gt;" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="140" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q2Auk95UIFfUWz-NXu3p-22" value="Armazenamento&amp;nbsp;&lt;div&gt;persistente&lt;/div&gt;" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="530" width="120" height="60" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
