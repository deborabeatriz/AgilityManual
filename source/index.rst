.. This is a comment. Note how any initial comments are moved by
   transforms to after the document title, subtitle, and docinfo.

.. agility.rst from: https://github.com/deborabeatriz/AgilityManual/

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

Os diversos tipos de usuário podem ser criados com os perfis necessários de acesso. São eles: usuário comum, cliente se empresa ou cidadão se prefeitura, funcionário da empresa ou prefeitura e atendente, que efetua a abertura de chamados no nome de outros solicitantes.

Usuário
^^^^^^^ 
Funcionário
^^^^^^^^^^^
Atendente
^^^^^^^^^



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
   :scale: 35 %
   :alt: cadastro de serviço

   
.. figure:: servico_conf2.png
   :scale: 35 %
   :alt: parâmetros do chamado


.. figure:: servico_conf3.png
   :scale: 35 %
   :alt: texto
 


Triagem Automática
------------------

Dependendo da configuração da triagem automática, um novo chamado pode ser classificado em três categorias distintas: 

* Aprovado Automaticamente: a classificação de aprovado pode ser trocado durante o tempo indicado no cadastro do serviço. Passado esse tempo, as tarefas do chamado ficam habilitadas para planejamento automático ou manual

* Em Verificação: a classificação em verificação precisa de ação manual. Um chamado classificado assim tem que ser aprovado ou reprovado manualmente para que seu planejamento automático ou manual seja habilitado

* Reprovado Automaticamente: a classificação de reprovado pode ser trocada durante o tempo indicado no cadastro do serviço. Passado esse tempo, o chamado é recusado, o usuário recebe mensagem com as razões da recusa e as tarefas do chamado não podem mais ser habilitadas para planejamento automático ou manual



Texto
^^^^^

Um chamado pode ser 

Imagem
^^^^^^

>>> print 'Python-specific usage examples; begun with ">>>"'
Python-specific usage examples; begun with ">>>"
>>> print '(cut and pasted from interactive Python sessions)'
(cut and pasted from interactive Python sessions)


Endereço
^^^^^^^^

>>> print 'Python-specific usage examples; begun with ">>>"'
Python-specific usage examples; begun with ">>>"
>>> print '(cut and pasted from interactive Python sessions)'
(cut and pasted from interactive Python sessions)


Prioridade
^^^^^^^^^^

>>> print 'Python-specific usage examples; begun with ">>>"'
Python-specific usage examples; begun with ">>>"
>>> print '(cut and pasted from interactive Python sessions)'
(cut and pasted from interactive Python sessions)


Code Blocks
-----------

.. parsed-literal::

    # parsed-literal test
    curl -O http://someurl/release-|version|.tar-gz


.. code-block:: json
    :caption: Code Blocks can have captions.

    {
    "windows": [
        {
        "panes": [
            {
            "shell_command": [
                "echo 'did you know'",
                "echo 'you can inline'"
            ]
            },
            {
            "shell_command": "echo 'single commands'"
            },
            "echo 'for panes'"
        ],
        "window_name": "long form"
        }
    ],
    "session_name": "shorthands"
    }

Emphasized lines with line numbers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: python
   :linenos:
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'

Sidebar
=======

.. sidebar:: Ch'ien / The Creative

    .. image:: static/yi_jing_01_chien.jpg

    *Above* CH'IEN THE CREATIVE, HEAVEN

    *Below* CH'IEN THE CREATIVE, HEAVEN

The first hexagram is made up of six unbroken lines. These unbroken lines stand for the primal power,
which is light-giving, active, strong, and of the spirit. The hexagram is consistently strong in character,
and since it is without weakness, its essence is power or energy. Its image is heaven.
Its energy is represented as unrestricted by any fixed conditions in space and is therefore conceived of as motion.
Time is regarded as the basis of this motion.
Thus the hexagram includes also the power of time and the power of persisting in time, that is, duration.

The power represented by the hexagram is to be interpreted in a dual sense in terms of its action
on the universe and of its action on the world of men. In relation to the universe, the hexagram expresses the strong,
creative action of the Deity. In relation to the human world, it denotes the creative action of the holy man or sage,
of the ruler or leader of men, who through his power awakens and develops their higher nature.

Code with Sidebar
-----------------

.. sidebar:: A code example

    With a sidebar on the right.

.. literalinclude:: test_py_module/test.py
    :language: python
    :caption: Literal includes can also have captions.
    :linenos:
    :lines: 1-40

References
==========

Footnotes
---------

.. [1] A footnote contains body elements, consistently indented by at
   least 3 spaces.

   This is the footnote's second paragraph.

.. [#label] Footnotes may be numbered, either manually (as in [1]_) or
   automatically using a "#"-prefixed label.  This footnote has a
   label so it can be referred to from multiple places, both as a
   footnote reference ([#label]_) and as a hyperlink reference
   (label_).

.. [#] This footnote is numbered automatically and anonymously using a
   label of "#" only.

.. [*] Footnotes may also use symbols, specified with a "*" label.
   Here's a reference to the next footnote: [*]_.

.. [*] This footnote shows the next symbol in the sequence.

.. [4] Here's an unreferenced footnote, with a reference to a
   nonexistent footnote: [5]_.

Citations
---------

.. [11] This is the citation I made, let's make this extremely long so that we can tell that it doesn't follow the normal responsive table stuff.

.. [12] This citation has some ``code blocks`` in it, maybe some **bold** and
       *italics* too. Heck, lets put a link to a meta citation [13]_ too.

.. [13] This citation will have two backlinks.


Here's a reference to the above, [12]_, and a [nonexistent]_ citation.

Here is another type of citation: `citation`

Glossary
--------

This is a glossary with definition terms for thing like :term:`Writing`:

.. glossary::
  
  Documentation
     Provides users with the knowledge they need to use something.

  Reading
     The process of taking information into ones mind through the use of eyes.

  Writing
     The process of putting thoughts into a medium for other people to :term:`read <Reading>`.

Targets
-------

.. _example:

This paragraph is pointed to by the explicit "example" target.
A reference can be found under `Inline Markup`_, above. `Inline
hyperlink targets`_ are also possible.

Section headers are implicit targets, referred to by name. See
Targets_, which is a subsection of `Body Elements`_.

Explicit external targets are interpolated into references such as "Python_".

.. _Python: http://www.python.org/

Targets may be indirect and anonymous.  Thus `this phrase`__ may also
refer to the Targets_ section.

__ Targets_

Here's a `hyperlink reference without a target`_, which generates an error.


Directives
==========

Contents
--------

.. contents:: :local:

These are just a sample of the many reStructuredText Directives. For others, please see:
http://docutils.sourceforge.net/docs/ref/rst/directives.html.


Centered text
-------------

You can create a statement with centered text with ``.. centered::``

.. centered:: This is centered text!

Images & Figures
----------------

Images
^^^^^^

An image directive (also clickable -- a hyperlink reference):

.. image:: static/yi_jing_01_chien.jpg
   :target: directives_

Figures
^^^^^^^

.. figure:: static/yi_jing_01_chien.jpg
   :alt: reStructuredText, the markup syntax

   A figure is an image with a caption and/or a legend:

   +------------+-----------------------------------------------+
   | re         | Revised, revisited, based on 're' module.     |
   +------------+-----------------------------------------------+
   | Structured | Structure-enhanced text, structuredtext.      |
   +------------+-----------------------------------------------+
   | Text       | Well it is, isn't it?                         |
   +------------+-----------------------------------------------+

   This paragraph is also part of the legend.

A figure directive with center alignment

.. figure:: static/yi_jing_01_chien.jpg
   :align: center

   This caption should be centered.

Admonitions
-----------

.. Attention:: Directives at large.

.. Caution:: Don't take any wooden nickels.

.. DANGER:: Mad scientist at work!

.. Error:: Does not compute.

.. Hint:: It's bigger than a bread box.

.. Important::
   - Wash behind your ears.
   - Clean up your room.

     - Including the closet.
     - The bathroom too.

       - Take the trash out of the bathroom.
       - Clean the sink.
   - Call your mother.
   - Back up your data.

.. Note:: This is a note.
   Equations within a note:
   :math:`G_{\mu\nu} = 8 \pi G (T_{\mu\nu}  + \rho_\Lambda g_{\mu\nu})`.

.. Tip:: 15% if the service is good.

    +---------+
    | Example |
    +=========+
    | Thing1  |
    +---------+
    | Thing2  |
    +---------+
    | Thing3  |
    +---------+

.. WARNING:: Strong prose may provoke extreme mental exertion.
   Reader discretion is strongly advised.

.. admonition:: And, by the way...

   You can make up your own admonition too.

Topics, Sidebars, and Rubrics
-----------------------------

.. sidebar:: Sidebar Title
   :subtitle: Optional Subtitle

   This is a sidebar.  It is for text outside the flow of the main
   text.

   .. rubric:: This is a rubric inside a sidebar

   Sidebars often appears beside the main text with a border and
   background color.

.. topic:: Topic Title

   This is a topic.

.. rubric:: This is a rubric

Target Footnotes
----------------

.. target-notes::

Replacement Text
----------------

I recommend you try |Python|_.

.. |Python| replace:: Python, *the* best language around

Compound Paragraph
------------------

.. compound::

   This paragraph contains a literal block::

       Connecting... OK
       Transmitting data... OK
       Disconnecting... OK

   and thus consists of a simple paragraph, a literal block, and
   another simple paragraph.  Nonetheless it is semantically *one*
   paragraph.

This construct is called a *compound paragraph* and can be produced
with the "compound" directive.

Download Links
==============

:download:`This long long long long long long long long long long long long long long long download link should be blue, normal weight text with a leading icon, and should wrap white-spaces <static/yi_jing_01_chien.jpg>`
