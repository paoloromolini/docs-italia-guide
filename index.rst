###################
Guida a Docs Italia
###################

Guida alla pubblicazione dei documenti della Pubblica Amministrazione su `Docs Italia <http://docs.italia/it>`_.
Titolo: {{ docsitalia_data.documents.title }}
Tags: {% for tag in docsitalia_data.documents.tags %}{{ tag }}{% endfor %}

.. toctree::
   :maxdepth: 2
   :caption: Indice dei contenuti

   index/che-cos-e-docs-italia.rst
   index/starter-kit.rst
   index/come-partecipare.rst
   index/scrivere-un-documento.rst
   index/pubblicare-un-documento.rst
   index/gestione-dei-documenti.rst
   index/appendice-1.rst
   index/appendice-2.rst
   index/appendice-3.rst

