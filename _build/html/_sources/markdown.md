# Bukele y las maras 
	[pagina 2](markdown-notebooks.md)

![alt text](bukele.jfif)

El sábado 26 de marzo de 2022 fue el día más violento en la historia reciente de El Salvador: la jornada cerró con 62 salvadoreños asesinados, según el balance preliminar presentado por la Policía Nacional Civil.

Para dimensionar la gravedad de lo ocurrido en el pequeño país centroamericano -un habitual en la parte alta de los ránking de los lugares más violentos del mundo-, basta señalar que desde que arrancó el año y hasta ese fin de semana aciago, se habían registrado en promedio 19 asesinatos por semana.

Nadie se ha reivindicado la matanza, pero en El Salvador pocos dudan que las maras o pandillas, que llevan décadas matando, extorsionando y dominando territorios, están detrás.

Luego de sucedida, la administración del presidente Nayib Bukele desató contra estas estructuras criminales la que quizá sea la ofensiva jurídica, mediática, policial y militar más intensa desde que echaron raíces en la sociedad, a inicios de los 90.

El 27 de marzo, el gobierno logró que el Congreso aprobara un estado de excepción, que entre otras cosas limita la libertad de los medios para difundir mensajes o comunicados de las pandillas, una medida que ha sido duramente criticada por los periodistas salvadoreños que la ven como un intento de imponer la versión oficial como la única posible.
## What is MyST?

MyST stands for "Markedly Structured Text". It
is a slight variation on a flavor of markdown called "CommonMark" markdown,
with small syntax extensions to allow you to write **roles** and **directives**
in the Sphinx ecosystem.

For more about MyST, see [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html).

## Sample Roles and Directivs

Roles and directives are two of the most powerful tools in Jupyter Book. They
are kind of like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
