{% extends "base.html" %}

{% block title %}<title>Temperatura</title>{% endblock %}


{% block content %}

<h1>Temperatura Ambiente</h1>
<div class="txt-container-color">
    xxxxx
    <img class="img-fluid" src="../static/images/Line-Chart-Vector-No-Background.png">
</div>
<br>
<div id="divfix">
    <table border="1" class="table table-light">
        <thead>
            <tr>
                <th>Tipo</th>
                <th>Média</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Hora</td>
                <td>XXXX</td>
            </tr>
            <tr>
                <td>Dia</td>
                <td>XXXX</td>
            </tr>
            <tr>
                <td>Semana</td>
                <td>XXXX</td>
            </tr>
        </tbody>
        <table border="1" class="table table-light">
            <thead>
                <tr>
                    <th>Tipo</th>
                    <th>Valor(°C)</th>
                    <th>Hora</th>
                    <th>data</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Maior temperatura</td>
                    <td>xx,x°C</td>
                    <td>XXXX</td>
                    <td>XXXX</td>
                </tr>
                <tr>
                    <td>Menor temperatura</td>
                    <td>xx,x°C</td>
                    <td>XXXX</td>
                    <td>XXXX</td>
                </tr>
            </tbody>
</div>


{% endblock %}

#divfix{
    display: flex; /*Permite que as tabelas fiquem uma ao lado da outra,
                     resolvendo o problema do comportamento em block das tabelas*/
}
