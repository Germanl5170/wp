---
ID: 6838
post_title: Prueba texto base (a agregar)
author: admin
post_excerpt: ""
layout: page
permalink: >
  https://tayudas.axoft.com/desarrollo/base_prueba/
published: true
post_date: 2018-07-18 10:53:50
---
<div id="content">
<p class="p_Definicion"><span class="f_Definicion">Esta opción permite definir prototipos o modelos de asientos, que luego pueden ser asociados a los <a href="?p=5954">Tipos de movimientos</a> o pueden ser asociados a movimientos desde <a href="?p=6749">Registración de movimientos</a>.</span></p>

</div>
[axcond pais=arg]Este texto es solamente para Argentina (borrar)[/axcond]. [axcond pais=ch]Este texto es solamente para Chile (borrar)[/axcond]
<div id="content">

&nbsp;
<p class="p_Normal">Estos modelos permiten en froma agilizar y facilitar la generación del mini - asiento del movimiento para el bien o los bienes incluidos.</p>
<p class="p_Normal"><span class="f__Negrita">Activo Fijo</span> de <strong>[axvar variable=astor_astorpro]</strong> divide los datos de un modelo de asiento en tres fichas: Principal, Cuentas contables y Observaciones.</p>
&nbsp;
<h4 class="p_TituloSolapa" style="border: none;"><span class="f_TituloSolapa">Principal del modelo de asiento</span></h4>
<p class="p_Normal">Esta ficha reúne los datos del encabezado del modelo de asiento.</p>
<p class="p_Normal">Al ingresar un modelo de asiento, usted debe asignarle un código, un tipo de asiento y un tipo de movimiento interno.</p>
&nbsp;
<p class="p_Normal"><span class="f__Campos">Código:</span> cada modelo que usted defina se identificará por este código. Es posible ingresar hasta 10 caracteres. El sistema valida que sea único, es decir, que no se repita en dos modelos.</p>
&nbsp;
<p class="p_Normal"><span class="f__Campos">Descripción:</span> es posible ingresar una descripción o referencia.</p>
&nbsp;
<p class="p_Normal"><span class="f__Campos">Tipo de asiento:</span> los modelos de asientos son de un tipo de asiento específico. Usted puede definir varios modelos de un mismo tipo de asiento. Puede elegir u tipo de asiento habilitado para el módulo de<span class="f__Negrita"> Activo Fijo</span>. Es un valor obligatorio.</p>
&nbsp;
<p class="p_Normal"><span class="f__Campos">[axvar variable=leyenda_glosa]:</span> por defecto se propone la [axvar variable=min_leyenda_glosa]por defecto para el tipo de asiento selecccionado. Puede modificarla eligiendo otra [axvar variable=min_leyenda_glosa] asociada al tipo de asiento seleccionado. Es un valor opcional.</p>
&nbsp;
<p class="p_Normal">Para más información sobre [axvar variable=min_leyenda_glosa]s para encabezados de asientos, consulte la ayuda en línea o el manual del módulo <span class="f__Negrita">Procesos generales</span>.</p>
&nbsp;
<p class="p_Normal"><span class="f__Campos">Tipo de movimiento interno:</span> este es un valor obligatorio para el modelo de asiento.</p>
&nbsp;
<h4><span class="f_TituloSolapa">Cuentas contables</span></h4>
En esta ficha, usted define el cuerpo o renglones del asiento modelo.
El sistema habilita los tipos contables según según el tipo de movimiento interno seleccionado y propone el modelo de asiento para el movimiento.
<h5>Detalle del modelo</h5>
</div>
Al agregar un nuevo modelo de asiento y pasar a esta solapa, el sistema propone el modelo de asiento de acuerdo al tipo de movimiento interno seleccionado en la solapa principal, usted tiene que asociarle las cuentas contables en el modelo.

&nbsp;

<em><strong>Número:</strong> </em>es el número de renglón del modelo. Este valor no puede modificarse.

&nbsp;

<em><strong>Código de cuenta:</strong></em> ingrese o seleccione la cuenta contable habilitada para Activo Fijo para el renglón.

&nbsp;

<em><strong>Descripción de la cuenta:</strong> </em>este dato se completa automáticamente al completar la columna "Cuenta".

&nbsp;

<em><strong>D/H:</strong></em> es el tipo de imputación que habitualmente lleva la cuenta en el modelo. Por defecto, se propone según el tipo de movimiento interno asociado al modelo.

&nbsp;

<strong><em>Tipo contable:</em></strong> esta columna se propone según el tipo de movimiento interno asociado al modelo.

&nbsp;

<strong><em>[axvar variable=stock_inventario]:</em></strong> por defecto se propone la descripción del tipo contable pero es posible modificarla.

&nbsp;

<em><strong>Reemplaza:</strong></em> por defecto este parámetro está activado y al momento de generar el mini-asiento para el movimiento tomará la cuenta configurada para el bien según el tipo contable del modelo de asiento.

&nbsp;

<em><strong>Edita cuenta:</strong></em> por defecto se propone este parámetro activado y al momento de generar el mini-asiento si genera asiento en el ingreso del movimiento, permite cambiar la cuenta contable.

&nbsp;
<h5>Detalle de apropiaciones</h5>
El ingreso de esta grilla es opcional y se habilita sólo si la cuenta contable usa auxiliares contables.

&nbsp;

<em><strong>Tipo de auxiliar:</strong> </em>ingrese o seleccione el código o descripción del auxiliar contable a utilizar en el modelo.

&nbsp;

<em><strong>Regla de apropiación:</strong></em> ingrese o seleccione el código o descripción de la regla de apropiación habilitadas para Activo Fijo a aplicar para el modelo.
La regla de apropiación de un modelo de asiento tiene prioridad sobre la regla de apropiación por defecto asociada al tipo de auxiliar.
Para más información, consulte en la ayuda en línea o en el manual del módulo <strong>Procesos generales</strong>, las opciones de la carpeta Auxiliares contables.

&nbsp;
<h4 class="p_TituloSolapa" style="border: none;"><span class="f_TituloSolapa">Modelo de asiento por tipo de comprobante interno</span></h4>
&nbsp;
<p class="p_Normal">En esta solapa se detallan los asientos propuestos por el sistema según el tipo de movimiento interno seleccionado.</p>
&nbsp;
<p class="p_Normal"><span style="font-weight: bold;">Modelo de asiento propuesto para el tipo de movimiento interno de Activación</span></p>

<div id="idcontent" class="nonscroll">
<div id="innerdiv">
<div id="TOGGLE0186A5" class="dropdown-toggle-body" style="text-align: justify; margin: 0.104in 0.208in; display: block; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-collapse: collapse; border-spacing: 0px; border-style: none;">
<tbody>
<tr>
<td style="vertical-align: top; border: #1777b1 0.031in; padding: 0px;">
<p class="p_Normal">En esta solapa se detallan los asientos propuestos por el sistema según el tipo de movimiento interno seleccionado.</p>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Activación</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta puente compra (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">COMP</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor de compra </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Ajuste por inflación</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación (R-)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEP</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación acumulada (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPAC</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación acumulada </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado del ajuste (R-, R+)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">AXI</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del ajuste por inflación</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Baja</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Seguros a cobrar (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">SEG</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Seguro a cobrar </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">No</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación acumulada (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPAC</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación acumulada </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado por baja (R-, R+)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">RDO</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado de la baja </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Baja por Venta</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación acumulada (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPAC</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación acumulada </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado por baja (R-, R+)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">RDO</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado de la baja </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Depreciación</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación (R-)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEP</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación</span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación acumulada (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPAC</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación acumulada </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Depreciación extraordinaria</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación extraordinaria (R-)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPEX</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación extraordinaria </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Depreciación acumulada (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">DEPAC</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor depreciación acumulada </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Mejora</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta mejora (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">MEJ</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor de la mejora </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta puente compra (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">COMP</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor de compra </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Revalúo</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta revalúo (R+)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">REV</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del revalúo </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal">Modelo de asiento propuesto para el tipo de movimiento interno de Revalúo para generar asiento de Resultado por tenencia</p>

<div style="text-align: justify; margin: 0.052in 0.208in 0.052in 0.625in; line-height: 2.4; text-indent: 0px; padding: 0px;">
<table style="border-spacing: 0.0104in; border-style: none;">
<tbody>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Cuenta </span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">D/H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Tipo contable  </span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Leyenda </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Reemplaza </span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; background-color: #c0c0c0; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif; font-weight: bold;">Edita cuenta</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Cuenta del bien (A)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">D</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">BIEN</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del bien </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
<tr>
<td style="height: 0.166in; width: 2.072in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Resultado por tenencia (R+,R-)</span></td>
<td style="height: 0.166in; width: 0.281in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">H</span></td>
<td style="height: 0.166in; width: 1.083in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">TCIA</span></td>
<td style="height: 0.166in; width: 2.197in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Valor del resultado por tenencia </span></td>
<td style="height: 0.166in; width: 0.864in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
<td style="height: 0.166in; width: 0.895in; vertical-align: top; padding: 0.01in;"><span style="font-size: 10pt; font-family: Arial,Helvetica,sans-serif;">Si</span></td>
</tr>
</tbody>
</table>
</div>
<p class="p_Normal"></p>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
<p class="p_Normal"><span style="font-weight: bold;">Valores posibles que podrá tomar el debe o el haber del renglón en el modelo de asiento según el tipo contable</span></p>

<ul>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">BIEN: </span>este tipo contable toma el valor afectado al bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta del bien</span> elegida en el bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">COMP:</span> este tipo contable toma el valor afectado al bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta de compra</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">DEP:</span> este tipo contable toma el valor afectado a la depreciación del bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta depreciación</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">DEPEX:</span> este tipo contable toma el valor afectado a la depreciación extraordinaria del bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta depreciación extraordinaria</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">DEPAC:</span> este tipo contable toma el valor afectado a la depreciación del bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta depreciación acumulada</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">MEJ: </span>este tipo contable toma el valor de la mejora afectado al bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta para mejoras</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">REV:</span> este tipo contable toma el valor del revalúo afectado al bien y si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta revalúo</span> elegida en el  bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">RDO:</span> este tipo contable toma el resultado calculado de la diferencia en el asiento entre las cuentas del debe y del haber. Si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta de baja</span> elegida en el bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">AXI:</span> este tipo contable toma el resultado calculado de la diferencia en el asiento entre las cuentas del debe y del haber. Si está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta resultado ajuste</span> elegida en el bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">TCIA:</span> este tipo contable toma el valor informado del revalúo para el bien. Si el tipo de movimiento de revalúo tiene activado el parámetro <span class="f__Campito">Genera asiento de Resultado por tenencia</span>" y además está activo en el modelo de asiento el parámetro <span class="f__Campito">Reemplaza</span> toma la <span class="f__Campito">Cuenta resultado tenencia</span> elegida en el bien.</li>
 	<li style="text-align: justify; text-indent: 0px; line-height: 2.4;"><span class="f__Negrita">SEG:</span> este tipo contable toma el valor informado del seguro a cobrar en el movimiento de baja y no es posible activar el parámetro <span class="f__Campito">Reemplaza</span>, siempre toma la cuenta contable informada en el modelo de asiento.</li>
</ul>
<p class="p_CodeExample"><span class="f_CodeExample"> </span></p>