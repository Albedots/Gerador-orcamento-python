# Projeto criado com a imersão Python da Empowerdata

## *Requisitos*:
* Interpretador `Python`.
* Biblioteca `FPDF`

#

## *Instalações*:

 ### Interpretador:
É recomendado baixar o interpretador pelo [python.org](https://www.python.org/downloads/) que é o site oficial da linguagem.


 ### Biblioteca:
No terminal do interpretador, digite:
>pip install fpdf

#

### *Modo de uso*:
* Executar o `gerador.py` com o interpretador.

## OBS:
Caso necessário, você poderá trocar o template para outro de sua escolha, porém, você tera de efetuar modificações no código fonte:

* No `pdf.image("template.png", x=0, y=0)`, troque o `template.png` pelo arquivo desejado.

* Troque as coordenadas dos elementos pela coordenada desejada, onde o primeiro valor é x e o segundo é y:
>pdf.text(115, 145, projeto)

>pdf.text(115, 160, horas_estimadas)

>pdf.text(115, 175, valor_hora)

>pdf.text(115, 190, prazo)

>pdf.text(115, 205, str(valor_total))
