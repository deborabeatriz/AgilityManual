.. This is a comment. Note how any initial comments are moved by
   transforms to after the document title, subtitle, and docinfo.

.. agility.rst from: https://github.com/deborabeatriz/AgilityManual/  Solicitante,Operador,Gestor 

.. |EXAMPLE| image:: static/yi_jing_01_chien.jpg
   :width: 1em

******* 
Agility
******* 

.. contents:: Conteúdo

Introdução
==========

Aqui você vai encontrar tudo que precisa saber sobre o Agility.

       
Cadastros
=========

Através dos cadastros é possível personalizar o Agility para a prefeitura ou empresa.

Usuários
-------- 

Os diversos tipos de usuário podem ser criados com os perfis necessários de acesso. São eles: usuário comum, cliente se empresa ou cidadão se governo, funcionário da empresa ou governo e atendente, que efetua a abertura de chamados no nome de outros solicitantes.

Usuário
^^^^^^^ 

Um usuário comum do Agility seria um cidadão, no caso de governo, ou um cliente, no caso de empresa privada.


Funcionário
^^^^^^^^^^^

Funcionário da empresa ou governo

Atendente
^^^^^^^^^

Efetua abertura de chamados no nome de outros solicitantes.



Temas e Serviços
----------------

Em cada instalação do Agility é possível configurar vários níveis de temas, com ícones próprios associados, atribuindo serviços ao último nível. Os serviços podem dar origem a abertura de chamados, ou podem ser informativos.


Temas
^^^^^^

A figura a seguir demonstra uma lista de temas configurados, sendo que os níveis são indicados na coluna pai. 

.. figure:: tema_conf.png
   :scale: 35 %
   :alt: tela de configuração de temas

A figura a seguir ilustra com são exibidos no menu de solicitação de serviços os temas que não têm um código de pai associado. Eles aparecem no primeiro nível.

.. figure:: tema.png
   :scale: 35 %
   :alt: resultado da configuração primeiro nível

A seguir estão ilustrados os temas associados ao nível 'Iluminação'.  

.. figure:: tema2.png
   :scale: 35 %
   :alt: resultado da configuração para 'iluminação'

Serviços
^^^^^^^^

Os temas do último nível são associados cada qual a um serviço. Por sua vez, o serviço pode ou não dar origem a um chamado, dependendo das informações indicadas em seu cadastro. 

A figura a seguir mostra a primeira aba do cadastro de um serviço. Quando o serviço é meramente informativo, a opção do cadastro 'Elegível Chamado' fica desabilitada, sendo que o serviço exibe apenas textos informativos indicados na aba "Textos Serviços". Já um serviço que pode dar origem a um chamado, tem a opção do cadastro 'Elegível Chamado' habilitada. Também exibe textos informativos. Além disso, serviços que podem dar origem a chamados têm vários parâmetros configuráveis informados na aba "Parâmetros Chamado".

.. figure:: servico_conf.png
   :scale: 45 %
   :alt: cadastro de serviço

   
.. figure:: servico_conf2.png
   :scale: 45 %
   :alt: parâmetros do chamado


.. figure:: servico_conf3.png
   :scale: 45 %
   :alt: texto
 


Triagem Automática
------------------

Dependendo da configuração da triagem automática, um novo chamado pode ser classificado em três categorias distintas: 

* Aprovado Automaticamente: a classificação de aprovado pode ser trocado durante o tempo indicado no cadastro do serviço. Passado esse tempo, as tarefas do chamado ficam habilitadas para planejamento automático ou manual

* Em Verificação: a classificação em verificação precisa de ação manual. Um chamado classificado assim tem que ser aprovado ou reprovado manualmente para que seu planejamento automático ou manual seja habilitado

* Reprovado Automaticamente: a classificação de reprovado pode ser trocada durante o tempo indicado no cadastro do serviço. Passado esse tempo, o chamado é recusado, o usuário recebe mensagem com as razões da recusa e as tarefas do chamado não podem mais ser habilitadas para planejamento automático ou manual



Texto
^^^^^

Há dois tipos de triagem distintas para texto

  Palavras Ofensivas
     Com base em um cadastro de palavras ofensivas, fornecido pelo Agility e mantido pela contratante, o Agility calcula quantas palavras ofensivas existem no texto. Seguindo os números máximos de palavras ofensivas configurados na triagem, o chamado pode ser aprovado automaticamente, reprovado automaticamente ou colocado em verificação nessa triagem.   
  Palavras Relevantes
     Com base em um cadastro de palavras irrelevantes, fornecido pelo Agility e mantido pela contratante, o Agility calcula quantas palavras relevantes existem de fato no texto. Seguindo os números mínimos de palavras relevantes configurados na triagem, o chamado pode ser aprovado automaticamente, reprovado automaticamente ou colocado em verificação nessa triagem.   


Imagem
^^^^^^

Utilizando inteligência artificial, o Agility analisa e classifica automaticamente as imagens anexadas ao chamado. As classificações possíveis quanto à probabilidade de serem ofensivas ou trotes são:

* Muito pouco provável

* Pouco provável

* Possível

* Provavelmente

* Muito Provavelmente

Seguindo as categorias configuradas na triagem, o chamado pode ser aprovado automaticamente, reprovado automaticamente ou colocado em verificação nessa triagem.   



Endereço
^^^^^^^^


Utilizando Google Maps, o Agility analisa e classifica automaticamente os endereços informados no chamado. As categorizações possíveis quanto à precisão do endereço são:

* GPS: obtido automaticamente através do GPS do celular

* Preciso: o endereço informado foi encontrado com precisão, ou seja, logradouro e número

* Entre dois pontos: foi encontrado um logradouro para o endereço informado, mas o local encontra-se entre dois números 

* Centro de rua ou polígono: foi encontrado um local para o endereço informado, mas encontra-se em um logradouro, sem ser possível determinar um número, ou em uma área

* Aproximado: não foi possível encontrar um logradouro ou uma área específica

* Manual: endereço digitado manualmente, sem uso do Google Maps

Seguindo as categorias configuradas na triagem, o chamado pode ser aprovado automaticamente, reprovado automaticamente ou colocado em verificação nessa triagem.   




Prioridade
^^^^^^^^^^

O Agility tem faixas de prioridade configuráveis.  A seguir, as figuras mostram exemplos com duas configurações de instalações distintas do Agility. 
Na primeira o cliente optou por três faixas de prioridade e na segunda, por cinco. As prioridades sempre começam em 0 e vão até o valor mais alto das faixas. Nos exemplos, vão de 0 a 100. A coluna valor representa o valor mais alto da faixa.

.. figure:: prioridade.png
   :scale: 45 %
   :alt: cadastro de serviço

   
.. figure:: prioridade2.png
   :scale: 45 %
   :alt: parâmetros do chamado

  Por serviço
     Cada serviço pode ter uma pontuação de prioridade padrão atribuída em seu cadastro. Essa prioridade recebe adições de pontuação de outras configurações de prioridade, citadas a seguir, se estiverem ativas.
  Por chamados vinculados, ou seja, identificados automaticamente ou manualmente como duplicados
     Ainda no cadastro de serviço, uma pontuação de prioridade pode ser configurada para que seja somada a cada novo vínculo recebido pelo chamado principal, ou seja, a cada novo chamado duplicado associado a ele. 
	 
.. figure:: servico_conf_pri.png
   :scale: 45 %
   :alt: pontuação prioridade serviço
	 
	 
  Por hierarquia
	 As hierarquias cadastradas, opcionalmente, possuem um pontuação de prioridade a ser somada ao chamado. Isso influi na pontuação dependendo da hierarquia do funcionário que solicitar um chamado.

.. figure:: hierarquia.png
   :scale: 45 %
   :alt: hierarquias
