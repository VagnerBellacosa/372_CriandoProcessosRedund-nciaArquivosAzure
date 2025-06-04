# 372_CriandoProcessosRedund-nciaArquivosAzure
Criando Processos de Redundância de Arquivos na Azure



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

Neste projeto prático, o objetivo é criar um processo completo de redundância de arquivos utilizando recursos do Microsoft Azure. Através do Azure Data Factory, você aprenderá a configurar uma infraestrutura necessária, incluindo conexões com ambientes on-premises (via Integration Runtime), bancos de dados SQL (Azure e locais) e armazenamento em blob storage. Aprenda o passo a passo, como criar linked services, datasets e pipelines para mover dados de uma tabela SQL on-premises para o Azure Data Lake, convertendo as informações em arquivos .TXT organizados por camadas (como raw/bronze). O hands-on também aborda validação, publicação e execução dos pipelines, com análise de performance e boas práticas de configuração.

**Azure****Azure Data Factory****Big Data**

------

###### Full-Stack

###### Intermediário

------

###### ESPECIALISTA

![author](https://hermes.dio.me/users/author/photos/61268924-081c-452f-8eab-e2dae323a9ba.jfif)

###### Carol Lavecchia

Founder & CTO at Invictus Data & AI, Invillia[**](https://www.linkedin.com/in/caroline-lavecchia/?originalSubdomain=br)



[DIO | Codifique o seu futuro global agora](https://web.dio.me/lab/criando-processos-de-redundancia-de-arquivos-na-azure/learning/862e8017-637d-4ce1-af70-59785b9f44c2)



##### Criando Processos de Redundância de Arquivos na Azure

<iframe id="ytc44" frameborder="0" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" title="Introdução" width="100%" height="100%" src="https://www.youtube.com/embed/ggzdoL91nEI?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1&amp;forigin=https%3A%2F%2Fweb.dio.me%2Flab%2Fcriando-processos-de-redundancia-de-arquivos-na-azure%2Flearning%2Fe6d52090-3abc-4528-b5b5-28f9fecf2e8f%3Fback%3D%2Ftrack%2Fmicrosoft-azure-databricks&amp;aoriginsup=1&amp;vf=6" data-gtm-yt-inspected-20="true" data-gtm-yt-inspected-25="true" style="box-sizing: inherit; max-width: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



##### Criando Processos de Redundância de Arquivos na Azure

<iframe id="ytc56" frameborder="0" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" title="Copiando uma informação de um ambiente para um Data Lake" width="100%" height="100%" src="https://www.youtube.com/embed/rO6iGNbPzdQ?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1&amp;forigin=https%3A%2F%2Fweb.dio.me%2Flab%2Fcriando-processos-de-redundancia-de-arquivos-na-azure%2Flearning%2F944d1e60-87b7-48ca-832b-e071a53abab2%3Fback%3D%2Ftrack%2Fmicrosoft-azure-databricks&amp;aoriginsup=1&amp;vf=6" data-gtm-yt-inspected-20="true" data-gtm-yt-inspected-25="true" style="box-sizing: inherit; max-width: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>





##### Criando Processos de Redundância de Arquivos na Azure

<iframe id="ytc68" frameborder="0" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" title="Pipelines" width="100%" height="100%" src="https://www.youtube.com/embed/NmxhcQzR6bE?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1&amp;forigin=https%3A%2F%2Fweb.dio.me%2Flab%2Fcriando-processos-de-redundancia-de-arquivos-na-azure%2Flearning%2Ff135138c-80d2-4894-8a35-cc3e25653da8%3Fback%3D%2Ftrack%2Fmicrosoft-azure-databricks&amp;aoriginsup=1&amp;vf=6" data-gtm-yt-inspected-20="true" data-gtm-yt-inspected-25="true" style="box-sizing: inherit; max-width: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



- Introdução
- Copiando uma informação de um ambiente para um Data Lake
- Pipelines
- Materiais de Apoio
